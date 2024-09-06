pipeline {
  agent {
    docker {
      image 'alpine'
    }

  }
  stages {
    stage('Stage 1') {
      steps {
        sh 'echo hello'
        validateDeclarativePipeline 'Jenkinsfile'
      }
    }

  }
  parameters {
    string(defaultValue: 'hello; ls /', name: 'SOME_STRING')
  }
}