pipeline {
  agent any
  stages {
    stage('build dockerfile') {
      steps {
        acrQuickTask(azureCredentialsId: 'de63ff5d-d67e-4d8fa-9a2b-026e9c0933a1', resourceGroupName: 'testResourceGroup2', registryName: 'containerresgistryneha', dockerfile: 'Dockerfile', gitRepo: 'https://github.com/kbhavik/docker-react.git', architecture: 'AMD64', sourceType: 'git')
      }
    }

  }
  environment {
    azureCredentialsId = 'de63ff5d-d67e-4d8f-9a2b-026e9c0933a1'
    resourceGroupName = 'testResourceGroup2'
    registryName = 'containerregistryneha'
  }
}