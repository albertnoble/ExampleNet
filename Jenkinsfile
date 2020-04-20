pipeline {
    agent any


    node('dotnet-22') {
        stages {
            stage ('Restore Stage') {
                sh "dotnet restore"
            }

            stage ('Testing Stage') {
                sh "dotnet test"
            }
            
        }
    }
}