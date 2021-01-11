pipeline {
    agent any
    stages {
        stage('Remove Docker Image') {
            when {
                expression { return current_status == "closed" && merged == true }
            }
            steps{
               script {
                 sh "echo hi"
            }
         }
        }
    }
}
