pipeline {
  agent any
  stages {
    stage('gitee') {
      steps {
        git(url: 'https://gitee.com/fe-jser/test.git', branch: 'master')
      }
    }
    stage('gitlab') {
      steps {
        git(url: 'http://116.196.121.11/JohnTheLegendSmith/vue-architecture.git', branch: 'master')
      }
    }
  }
}