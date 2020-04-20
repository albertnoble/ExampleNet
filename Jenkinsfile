pipeline {
    agent any
        stages {

            stage ('Testing Stage') {
		steps{ 
                    sh "dotnet add package Microsoft.NETCore.Platforms --version 3.1.0"
                    sh "dotnet test" 
                }
            }
            
        }
}