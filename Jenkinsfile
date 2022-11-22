pipeline {
    agent {
      docker {
        image 'node:10'
      }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'ls -la'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
