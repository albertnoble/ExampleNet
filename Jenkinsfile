node {
    stage 'Checkout'
        checkout scm

    stage 'Build'
        sh 'nuget restore ExampleNet.sln'
}