pipeline {
    agent { docker { image 'hashicorp/terraform' } }
    stages {
        stage('build') {
            steps {
                sh 'terraform version'
            }
        }
    }
}
