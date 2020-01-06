pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build 'job.1 (None)'
      }
    }

    stage('execute') {
      steps {
        build 'job.2 (None)'
      }
    }

    stage('') {
      steps {
        echo 'Integration complete'
      }
    }

  }
}
