pipeline {
    agent any

    stages {
        stage('dev') {
            when {
                branch 'feature'
            }
            steps {
                echo 'from feature branch...,,...'
            }
        }
        stage('QA') {
            when {
                branch 'develop'
            }
            steps {
                echo 'from develop branch'
            }
        }
        stage('prod') {
            when {
                branch 'main'
            }
            steps {
                //dadsaaaaa
                echo 'from master branch'
            }
        }
    }
}
