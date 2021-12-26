@Library('jenkinslib') _

def tools = new org.devops.tools()

hello()

pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                script {
                    tools.PrintMes('hello rxdxxxx')
                }
            }
        }
    }
}
