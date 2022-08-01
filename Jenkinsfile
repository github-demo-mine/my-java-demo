pipeline {
    agent any
    tools { 
        maven 'M2'
        jdk 'java'    }    
    
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                ''' 
            }
        }        
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
