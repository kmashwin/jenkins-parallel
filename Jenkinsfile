pipeline {
  agent any
  triggers {
    pollSCM '* * * * *'
  }
  stages {
    stage('stage1') {
      steps {
	sh 'sleep 2'
      }

    }
    stage('stage2') {
      steps {
	sh 'sleep 4'
      }

    }
    stage('stage3') {
      steps {
	sh 'sleep 6'
      }

    }
    stage('stage4') {
      steps {
	sh 'sleep 8'
      }

    }
  }
}
