pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh 'echo \'hello ,stage 1\''
      }
    }

    stage('stage 2') {
      steps {
        sh 'echo \'hello ,stage 2\''
        git(url: 'https://github.com/Mallika4679/mounika.git', branch: 'main', poll: true)
      }
    }

  }
}