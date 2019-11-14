pipeline {
    agent {
        docker { image 'linux' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'hostname'
            }
        }
    }
}
