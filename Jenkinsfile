pipeline {
    agent any

    stages {
        stage('checkout & clean') {
            steps {
                echo '1. checkout code'
                git url: 'https://github.com/Viralpatel489/helloworld.git' , branch: 'main'
                echo '2. clean workspace'
                sh 'mvn clean'                
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying1234....'
            }
        }
    }
}