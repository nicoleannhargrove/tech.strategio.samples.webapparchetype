
pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -version'
            }
        }
        stage('Unit Test') {
            steps{
                echo 'In Stage Unit Test'
            }
        }
    }
}
