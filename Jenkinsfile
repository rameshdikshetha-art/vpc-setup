pipeline {
    agent any

    stages {
        stage('Verify') {
            steps {
                sh '''
                echo "Pipeline is working"
                pwd
                ls -lrt
                '''
            }
        }
    }
}