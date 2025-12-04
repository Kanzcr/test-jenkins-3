pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/username/test-jenkins-3.git'
            }
        }

        stage('Build') {
            steps {
                sh '''
                    cd test-jenkins-3
                    echo Running build step...
                '''
            }
        }

        stage('Test') {
            steps {
                sh '''
                    cd test-jenkins-3
                    echo Running test step...
                '''
            }
        }
    }
}
