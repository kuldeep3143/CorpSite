pipeline {
    agent any
   
    stages {
        stage('CI') {
            steps {
                snDevOpsStep()
            }
        }
        stage('UAT deploy') {
            steps {
                snDevOpsStep()
            }
        }
        stage('UAT test') {
            steps {
                snDevOpsStep()
            }
           
        }
        stage('deploy') {
            steps {
                snDevOpsStep()
                snDevOpsChange()
                
            }
        }
    }
}
