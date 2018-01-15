pipeline {
    agent any

    stages {
        stage('Build') {                        
            steps {
                echo 'Building..'
                sleep(5) {
                    echo 'Waiting for 5 seconds'
                }
                echo 'Built completed in 5 seconds'
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