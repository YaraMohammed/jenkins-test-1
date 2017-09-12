pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo $BUILD_NUMBER';
                sh 'javac HelloWorld.java';
                sh 'jar cf "$BUILD_NUMBER".jar HelloWorld.class';
                sh 'ls'
            }
        }
        
    }
}
