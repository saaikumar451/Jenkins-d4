pipeline {
    agent any
    tools {
        maven 'MVN_PATH'
    }
    stages{
        stage ('Maven'){
            steps{
                echo "****** Maven Version ******"
                sh 'mvn --version'
            }
        }
    }
}
