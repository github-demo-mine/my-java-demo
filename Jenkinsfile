pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'this is my mvn test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Here is my mvn application deployment'
            }
        }
    }
}
