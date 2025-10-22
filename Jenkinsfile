pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git url: 'https://github.com/Viralpatel489/helloworld.git' , branch: 'main'
                echo 'Building..'
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