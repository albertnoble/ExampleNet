pipeline {
    agent any
        stages {
            stage ('Restore Stage') {
		steps{ 
                        sh "export PATH=${PATH}:${HOME}/.dotnet/tools"
			sh "dotnet restore" 
		}   
            }

            stage ('Testing Stage') {
		steps{ 
                    sh "export PATH=${PATH}:${HOME}/.dotnet/tools"
                    sh "dotnet test" 
                }
            }
            
        }
}