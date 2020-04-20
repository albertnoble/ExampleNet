node {
    stage 'Checkout'
        checkout scm

    stage 'Build'
        sh 'dotnet restore ExampleNet.sln'
}