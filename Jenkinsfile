pipeline {
    agent any

    stages {
        stage('Build') {                        
            steps {
                echo 'Building..'
                sleep {
                    time: 5
                    unit: seconds
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