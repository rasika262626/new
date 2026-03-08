pipeline {
    agent any

    triggers {
        githubPush()
        cron('H/5 * * * *')
    }

    stages {
        stage('Build') {
            steps {
                echo 'Build triggered by GitHub push or cron schedule'
            }
        }
    }
}
