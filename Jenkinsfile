pipeline {
  agent any
  stages {
    stage('build dockerfile') {
      steps {
        acrQuickTask(azureCredentialsId: 'de63ff5d-d67e-4d8f-9a2b-026e9c0933a1', resourceGroupName: 'testResourceGroup2', registryName: 'containerresgistryneha', gitRepo: 'https://github.com/NehaOberoi92/docker-react.git')
      }
    }

  }
}
