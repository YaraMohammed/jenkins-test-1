pipeline {
    agent any
    parameters {
        string(name: 'VAR', defaultValue: 'Non', description: 'test pamateres passing?')
    }

    stages {
        stage('Build') {
            steps {
                /*
                sh 'echo $BUILD_NUMBER';
                sh 'javac HelloWorld.java';
                sh 'jar cf HelloWorld_V."$BUILD_NUMBER".jar HelloWorld.class';
                sh 'ls'
                */
                sh 'echo ${VAR}'
            }
        }
        
    }
}
