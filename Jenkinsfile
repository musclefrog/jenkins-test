// README 수정 감지 -> echo 메시지 출력

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
                echo 'Checked out source'
            }
        }
        stage('Build') {
            steps {
                echo 'This is a test build triggered by a README change.'
            }
        }
    }
}