pipeline {
    agent any

    stages {
        stage('Fetch') {
            steps {
                echo 'Fetching from repo'
                git 'https://github.com/rasika262626/new.git'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Building in Progress'
                bat 'javac hello.java'
            }
        }
        stage('execute') {
            steps {
                echo 'Executed'
                bat 'java hello'
            }
        }
        
    }
}
