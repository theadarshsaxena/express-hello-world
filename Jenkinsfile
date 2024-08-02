pipeline {
  agent any
  stages{
    stage("checkout"){
      git "https://github.com/AkashSivakumar/express-hello-world"
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
