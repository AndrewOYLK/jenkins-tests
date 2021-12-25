pipeline {
  agent any

  // 全局环境变量
  environment {
    FLAG = 'true'
    DB_ENGINE = 'innodb'
  }

  stages {
    stage('build') {
      environment {
        STAGE_FLAG = 'false'
      }

      steps {
        sh 'printenv'
      }
    }
  }
}