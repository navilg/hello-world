pipeline {
  agent any
  stages {
    stage('WS') {
      steps {
        ws(dir: '/home/ubuntu') {
          sh '''echo "hello"
'''
          sh 'echo "2"'
        }

        sh 'echo "Out"'
      }
    }

  }
}