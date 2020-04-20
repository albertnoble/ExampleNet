node {
    stage 'Checkout'
        checkout scm

    stage 'Restore'
        sh 'dotnet restore ExampleNet.sln'

    stage 'Build'
        sh 'dotnet build ExampleNet.sln'

    stage 'Test'
        sh 'dotnet test ExampleNet.sln'
}