pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "build stage perfomred"
            }
        }
        stage('Test') {
            steps {
                echo "test stage perfomred"
            }
        }
        stage('Deploy') {
            when { tag "release-*" }
            steps {
                echo 'Deploying only because this commit is tagged...'
                
            }
        }
    }
