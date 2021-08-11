pipeline {
    agent any

    stages {
        stage('One') {
            steps {
                sh 'cd roboshop-shell-scripting ; terraform init'
            }
        }

         stage('Two') {
             steps {
                sh 'terraform apply -auto-approve'
             }
         }
    }
}
