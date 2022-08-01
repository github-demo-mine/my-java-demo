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
