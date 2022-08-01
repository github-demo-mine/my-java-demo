pipeline {
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
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
