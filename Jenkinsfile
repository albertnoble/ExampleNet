pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                    sh 'dotnet build'
            }
        }

        stage ('Testing Stage') {

            steps {
                    sh 'dotnet test'
            }
        }
        
    }
}