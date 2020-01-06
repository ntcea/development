pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build 'job.1 (기본)'
      }
    }

    stage('execute') {
      steps {
        build 'job.2 (기본)'
      }
    }

    stage('') {
      steps {
        echo 'Integration complete'
      }
    }

  }
}
