pipeline {
    agent any
    stages {
      stage ('Docker Build') {
          steps {
            echo 'Building...'
            sh "docker-compose build"
            echo 'Build Finished'
          }
        }
    }
}