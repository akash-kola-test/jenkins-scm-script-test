echo "hello I'll run every time"

pipeline {
    agent any
    parameters {
      string defaultValue: 'hello; ls /', name: 'SOME_STRING'
    }
    stages {
        stage('Stage 1') {
            steps {
                sh ('echo ${SOME_STRING}')
            }
        }
    }
}
