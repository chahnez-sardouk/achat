pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
          stage('CHECKOUT GIT') {

      steps {
          git branch: 'main',
        url: 'https://github.com/chahnez-sardouk/achat.git'
      }
    }
}}
