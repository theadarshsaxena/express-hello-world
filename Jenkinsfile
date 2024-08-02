pipeline {
  agent any
  stages{
    stage("debug"){
      steps {
        script {
          sh 'ls'
          sh 'pwd'
        }
      }
    }
    stage("install"){
      steps {
        script {
          sh 'npm install'
        }
      }
    }
    stage("build") {
      steps{
        script {
          sh 'npm run build'
        }
      }
    }
  }
}
