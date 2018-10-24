# Jenkins file to run pipeline as code

pipeline {
    agent any
    stages {
        stage ("Build") {
            steps {
                sh "mvn clean package"
            }
            
        }
    }
}