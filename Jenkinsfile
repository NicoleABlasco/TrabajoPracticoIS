pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/NicoleABlasco/TrabajoPracticoIS.git', branch: 'main')
        withGradle() {
          sh 'chmod +x gradlew'
          sh 'gradlew init'
          sh 'gradlew bootRun'
        }

      }
    }

    stage('Test') {
      steps {
        sh 'echo'
      }
    }

    stage('Validate') {
      steps {
        sh 'echo'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo'
      }
    }

  }
}