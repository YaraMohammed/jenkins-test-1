pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo $BUILD_NUMBER';
                sh 'javac HelloWorld.java';
                sh 'java HelloWorld';
            }
        }
        
    }
}
