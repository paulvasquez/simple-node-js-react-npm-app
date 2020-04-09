pipeline {
    agent {
        docker {
            image 'node:8.12.0'
        }
    }
    environment {
        CI = 'true' 
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm -v'
            }
        }
        // stage('Test') { 
        //     steps {
        //         sh './jenkins/scripts/test.sh' 
        //     }
        // }
    }
}
