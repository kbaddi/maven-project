# Jenkins file to initiate build

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