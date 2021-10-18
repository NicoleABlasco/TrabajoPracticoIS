pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/NicoleABlasco/TrabajoPracticoIS.git', branch: 'main')
        withGradle() {
          sh 'chmod +x gradlew'
        }

      }
    }

  }
}