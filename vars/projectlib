def call(String test) {
  pipeline {
    agent any
    tools {
      maven 'maven'
    }
  stages{  
     stage('parallel1'){
      parallel{
        stage('actions1'){
          steps{
            sh 'pwd'
          }
        }
        stage('actions2'){
          steps{
            sh 'lscpu'
          }
        }
      }
    }
     stage('parallel2'){
      parallel{
        stage('actions3'){
          steps{
            sh 'pwd'
          }
        }
        stage('actions4'){
          steps{
            sh 'lscpu'
          }
        }
      }
    }
     stage('parallel3'){
      parallel{
        stage('actions5'){
          steps{
            sh 'pwd'
          }
        }
        stage('actions6'){
          steps{
            sh 'lscpu'
          }
        }
      }
    }
     stage('parallel4'){
      parallel{
        stage('actions7'){
          steps{
            sh 'pwd'
          }
        }
        stage('actions8'){
          steps{
            sh 'lscpu'
          }
        }
      }
    }
  }
  }
}
