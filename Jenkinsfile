pipeline {
    agent any
    stages {
        stage('Remove Docker Image') {
            when {
                expression { return env.current_status == "closed" && env.merged == true }
            }
            steps{
               script {
                 sh "echo hi"
             }
         }
        }
    }
}
