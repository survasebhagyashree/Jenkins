pipeline {
  agent {
    docker { image 'node:16-alpine' }
}
Stages {
  stage ('nodejs_version check') {
    steps {
      sh 'node --version'
    }
  }
}
}
