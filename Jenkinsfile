pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage('Maven build') {
            steps {
                sh 'mvn -version'
            }
        }
    }
}
