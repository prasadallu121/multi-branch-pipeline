pipeline {
    agent any
    stages {
        stage('Build Master') {
            when {
            branch 'master'
            }
            steps {
                echo "Building Master..."
            }
        }
        stage('Build Dev') {
            when {
            branch 'Dev'
            }
            steps {
                echo "Building Dev........"
            }

        }
    }
}
