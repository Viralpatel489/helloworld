pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git branch: static 'main', url: 'https://github.com/Viralpatel489/helloworld.git'
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