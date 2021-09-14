pipeline {
  node any
  stages {
    stage('build-main') {
      when {
        branch main
      }
      steps{
        sh "echo building from main branch"
      }
    }
    stage('build-master) {
          when {
            branch master
          }
          steps{
            sh "echo building from master branch"
          }
       }
  }
}
