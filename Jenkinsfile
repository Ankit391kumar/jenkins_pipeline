pipeline {
    agent none

    stages {
        stage ('stage_1') {
            agent {lable 'slave1'}
            steps {
                sh '''
                echo "this ti stage_1"
                ls -lrt
                '''
            }
        }
        stage ('stage_2') {
            agent {lable 'slave2'}
            steps {
                sh '''
                echo "this ti stage_2"
                ls -lrt
                '''
            }
        }
    }
}
