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
                expression {
                    branch 'development'
                }
            }
            steps {
                echo 'Deploying'
            }
        }
    }
}