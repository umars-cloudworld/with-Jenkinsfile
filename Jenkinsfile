pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
         stage('Test') {
            steps {
                echo 'Testing'
            }
        }
         stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
    post{
        always{
            emailext body: 'hello, from jenkins', subject: 'jenkins', to: 'mahnoorshafique45@gmail.com'
        }

    }
}