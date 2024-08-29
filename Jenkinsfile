pipeline {
    agent any

    stages {
        stage('development') {
            steps {
                echo 'Hello World-development'
                bat 'git clone \'https://github.com/tanishkarakte21/City-Weather-app.git\''
            }
        }
        stage('QA'){
            steps{
                echo 'Hello World-QA'

            }
        }
        stage('operations'){
            steps{
                echo 'Hello World-operations'
            }
        }
    }
}
