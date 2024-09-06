pipeline {
    agent none
    stages {
        stage('Stage 1') {
            agent {
                docker { image: 'alpine' }
            }
            steps {
                sh ('echo hello')
            }
        }
    }
}
