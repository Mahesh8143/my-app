pipeline {
    agent any 
    stages {
        stage('clean') { 
            steps {
               // sh "mvn clean"
                echo "Hello Mahesh"
            }
        }
        stage('Test') { 
            steps {
                sh "mvn test"
            }
        }
        stage('Package') { 
            steps {
                sh "mvn package"
            }
        }
    }
}
