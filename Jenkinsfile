pipeline {
  agent any

  stages {
    stage("This is stage 1") {
      steps {
        git branch: 'main', url: 'https://github.com/Nilakshi23/Stages.git'
      }
    }

    stage("This is stage 2") {
      steps {
        echo 'Cool stuff goes here!'
      }
    }
       stage("This is stage 3") {
      steps {
        sh '''
              pwd
              pip3 install httplib2
              python3 quickstart.py
              '''
      }
      }
    
  }
}
