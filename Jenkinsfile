pipeline {
    agent { docker { image 'maven:3.9.9-eclipse-temurin-21-alpine' } }
    stages {
        stage('Build') {
            steps {
                sh 'mvn --version'
                echo 'Building the project...'
            }
        }
    }
}
