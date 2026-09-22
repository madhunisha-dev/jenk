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
                bat 'python sum.py'
            }
        }
    }
}