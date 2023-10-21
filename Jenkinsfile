pipeline {
    agent any

    stages {
        stage('Maven Version check') {
            steps {
                bat 'mvn -v'
            }
        }
        stage('Running the Test') {
            steps {
                bat 'mvn clean test'
            }
        }
        stage('Say Hello') {
            steps {
                echo 'Hello Team MicroDegree'
            }
        }
    }
}