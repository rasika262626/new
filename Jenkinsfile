pipeline {
    agent any

    triggers {
        githubPush()
        cron('H/5 * * * *')
    }

    stages {

        stage('Build') {
            steps {
                echo 'Building the project'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application'
            }
        }
    }
}
