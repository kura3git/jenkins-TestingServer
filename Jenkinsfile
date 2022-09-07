pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "GOD DID!"'
      sh '''
        echo "This will list current dir content from latest"
        ls -lh
        pwd
        '''
      }
    }
  }
}
