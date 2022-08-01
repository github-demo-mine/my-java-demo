pipeline {
    agent any
    tools {
        maven 'Maven 3.8.6'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
              sh 'echo "this is my mvn test"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Here is my mvn application deployment"'
            }
        }
    }
}
