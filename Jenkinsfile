// Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                retry(3) {
                    sh 'echo "hello world"'
                }

                timeout(time: 3, unit: 'MINUTES') {
                    sh 'echo "hello world"'
                }
            }
        }
    }
}
