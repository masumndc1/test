pipeline {
    agent { label 'test-ubuntu16' }
    stages {
        stage('build') {
            steps {
                sh 'python test.py'
                sh 'ifconfig'
            }
        }
    }
}
