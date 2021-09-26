pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Compiıing the java source code'
                sh 'javac Hello.java'
            }
        }    
        stage('run') {
            steps {
                echo 'Running the complied java code.'
                sh 'java Hello'
            }        
        }
    }
}