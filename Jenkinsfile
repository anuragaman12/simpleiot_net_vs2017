pipeline {
  agent {
    node {
      label 'appscan pipeline'
    }

  }
  stages {
    stage('clone repository') {
      steps {
        git(url: 'https://github.com/endangeredspecies/simpleiot_net_vs2017.git', branch: 'master')
      }
    }
  }
}