pipeline {
  agent {
    docker { image 'node:16-alpine' }
}
stages {
  stage ('nodejs_version check') {
    steps {
      sh 'node --version'
    }
  }
}
}
