pipeline {
    agent any
    stages {
        stage('Remove Docker Image') {
            when {
                expression { return params.current_status == "closed" && params.merged == true }
            }
            steps{
               script {
                 sh "echo hi"
            }
         }
        }
    }
}
