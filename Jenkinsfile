pipeline {
  agent {
    node {
      label 'principal'
    }

  }
  stages {
    stage('Stage_1  Build') {
      steps {
        echo 'Stage_1 step 1'
      }
    }

    stage('Stage_2 - Test') {
      steps {
        echo 'Running Unit test....'
        echo 'Running Integracion test....'
        echo 'Running Aceptation test....'
      }
    }

    stage('Stage_3 - Deploy') {
      steps {
        echo 'Deploying artifact'
      }
    }

  }
}