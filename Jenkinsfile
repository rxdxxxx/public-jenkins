@Library('jenkinslib') _

def tools = new org.devops.tools()

// hello()

pipeline {
    agent any
    options {
      // 执行语句时,打印时间戳
      timestamps()
      // 隐藏 gitcheckout 信息
      skipDefaultCheckout()
      // 禁止并行
      disableConcurrentBuilds()
      // 超时限制
      timeout(time:1,unit:'HOURS')
    }
    stages {
        stage('Example') {
            steps {
                script {
                    tools.PrintMes('hello rxdxxxx','red')
                }
            }
        }
    }
}
