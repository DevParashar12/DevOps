pipeline {
    agent any

    stages {

        stage('Maven Compile') {
            steps {
                bat '"D:\\Download\\apache-maven-3.9.16-bin\\apache-maven-3.9.16\\bin\\mvn.cmd" compile'
            }
        }

        stage('Maven Package') {
            steps {
                bat '"D:\\Download\\apache-maven-3.9.16-bin\\apache-maven-3.9.16\\bin\\mvn.cmd" clean package'
            }
        }

    }
}
