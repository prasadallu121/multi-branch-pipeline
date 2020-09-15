pipeline {
    agent any
    stages {
        stage('Build') {
        when {
        tag 'v*.0'
        }
            steps {
            echo 'Hello World building tag'
            }
        }
    }
}
