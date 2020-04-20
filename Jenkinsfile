pipeline {
    agent any
        stages {
            stage ('Restore Stage') {
		steps{ sh "dotnet restore" }   
            }

            stage ('Testing Stage') {
		steps{ sh "dotnet test" }
            }
            
        }
}