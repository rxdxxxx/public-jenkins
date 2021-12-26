@Library('jenkinslib') _

def tools = new org.devops.tools()

// hello()

pipeline {
    agent any
    options {
      timestamps()
      skipDefaultCheckout()
      disableConcurrentBuilds()
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
