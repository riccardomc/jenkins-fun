pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Example Deploy') {
            steps {
                echo 'Deploying'
                error("Oh nee! This is bad!")
            }
        }
    }
}
