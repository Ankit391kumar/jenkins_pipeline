pipeline {
    agent any

    stages {
        stage ('stage_1') {
            steps {
                sh '''
                echo "this ti stage_1"
                ls -lrt
                '''
            }
        }
        stages {
        stage ('stage_2') {
            steps {
                sh '''
                echo "this ti stage_2"
                ls -lrt
                '''
            }
        }
    }
}
