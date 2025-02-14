pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/mrinalpravi/jenkins-trigger.git/'
            }
        }
        stage('Build') {
            steps {
                echo 'Code committed! Pipeline triggered successfully!'
            }
        }
    }
}
