pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building app'
            }
        }
         stage('Test') {
            steps {
                echo 'Testing app'
            }
        }
         stage('Deploy') {
            steps {
                echo 'Deploying app'
            }
        }
    }
    post{
        always{
            emailext body: 'hello, from jenkins', subject: 'jenkins', to: 'mahnoorshafique45@gmail.com'
        }

    }
}