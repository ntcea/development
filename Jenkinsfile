pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build 'job.1'
      }
    }

    stage('execute') {
      steps {
        build 'job.2'
      }
    }

    stage('') {
      steps {
        echo 'Integration complete'
      }
    }

  }
}