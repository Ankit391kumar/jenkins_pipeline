pipeline {
    agent none

    stages {
        stage ('stage_1') {
            agent { label 'slave1' }
            steps {
                sh '''
                echo "this ti stage_1"
                ls -lrt
                sleep 30
                '''
            }
        }
        stage ('stage_2') {
            agent { lable 'slave2' }
            steps {
                sh '''
                echo "this ti stage_2"
                ls -lrt
                sleep 30
                '''
            }
        }
    }
}
