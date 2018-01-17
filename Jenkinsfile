pipeline {
    agent any

    stages {

        when { branch 'master' }

        stage('Build Tier One') {                        

            steps {
                echo 'Building..'
                sleep(10) {
                    echo 'Waiting for 10 seconds'
                }
                echo 'Built completed in 10 seconds'
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