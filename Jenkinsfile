pipeline {
    agent any
        stages {
            stage ('Restore Stage') {
                sh "dotnet restore"
            }

            stage ('Testing Stage') {
                sh "dotnet test"
            }
            
        }
}