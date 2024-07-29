pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
               git branch: 'main', url: 'https://github.com/deepu412/hook.git' 
            }
        }
         stage('Hello') {
            steps {
                sh "terraform init"
            }
        }
         stage('Hello') {
            steps {
                sh "terraform apply -auto-approve"
            }
        }
    }
}
