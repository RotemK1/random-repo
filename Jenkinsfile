@Library("shared-library") _

pipeline {
    agent{
        any
    }
    stages {
        stage('Build') {
            steps {
                testVar(name:"${env.JOB_NAME}")
                                
            }
        }
    }
}
