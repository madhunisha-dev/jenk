pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/madhunisha-dev/summm.git'
            }
        }
        stage('Build') {
            steps {
                bat 'C:\Users\madhu\AppData\Local\Programs\Python\Python312\python.exe sum.py'
            }
        }
    }
}