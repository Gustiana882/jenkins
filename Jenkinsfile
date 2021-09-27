pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello jenkins'
            }
        }
        stage('Example Deploy') {
            when {
                branch 'development'
            }
            steps {
                echo 'Deploying'
            }
        }
    }
}