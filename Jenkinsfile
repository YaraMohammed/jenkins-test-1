pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo $BUILD_NUMBER';
                sh 'mvn --version';
            }
        }
        
    }
}
