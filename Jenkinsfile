
pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean compile'
            }
        }
        stage('Unit Test') {
            steps{
                echo 'In Stage Unit Test'
            }
        }
    }
}
