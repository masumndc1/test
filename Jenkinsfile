pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python test.py'
                sh 'ifconfig'
            }
        }
    }
}
