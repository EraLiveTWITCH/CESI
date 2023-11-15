pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/EraLiveTWITCH/docker-node-example', branch: 'main')
        dir(path: 'CESI/docker.build docker-node-example')
      }
    }

  }
}