pipeline {
    agent any 

    stages {
        stage('Terraform Init') {
            steps {
                sh "terraform init -backend-config=env-${ENV}/"
            }
        }
    }
}