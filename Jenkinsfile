pipeline {
    agent any

    stages {
        stage ('Build Stage') {

            steps {
                    bat "\"C:/Program Files/dotnet/dotnet.exe\" restore \"ExampleNet/ExampleNet.sln\""
                    bat "\"C:/Program Files/dotnet/dotnet.exe\" build \"ExampleNet/ExampleNet.sln\""

            }
        }

        stage ('Testing Stage') {

            steps {
                    sh 'dotnet test'
            }
        }
        
    }
}