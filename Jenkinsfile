pipeline {
    agent any
        stages {

            stage ('Testing Stage') {
		steps{ 
                    sh "dotnet add package Microsoft.NETCore.App --version 2.2.8"
                    sh "dotnet test" 
                }
            }
            
        }
}