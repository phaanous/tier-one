pipeline {
    agent any

    stages {

        stage('Build Tier One') {

            when { branch 'master' }

            steps {
                echo 'Building..'
                sleep(10) {
                    echo 'Waiting for 10 seconds'
                }
                echo 'Built completed in 10 seconds'
            }        

        }

        stage('Test') {

            when { branch 'master' }

            steps {
                echo 'Testing..'
            }

        }

        stage('Deploy') {

            when { branch 'master' }

            steps {
                echo 'Deploying....'
            }

        }

    }

}