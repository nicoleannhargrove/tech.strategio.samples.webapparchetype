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
        stage('Test') {
            steps {
		echo "in Test"
            }
        }
    }
}
