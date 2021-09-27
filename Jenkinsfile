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
                echo branch
            }
            steps {
                echo 'Deploying'
            }
        }
    }
}