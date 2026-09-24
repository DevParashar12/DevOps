pipeline {
    agent any

    stages {

        stage('Maven Compile') {
            steps {
                dir('hello-maven') {
                    bat 'mvn compile'
                }
            }
        }

        stage('Maven Package') {
            steps {
                dir('hello-maven') {
                    bat 'mvn clean package'
                }
            }
        }

    }
}
