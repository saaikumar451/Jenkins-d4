pipeline {
    agent any
    tools {
        maven 'MVN_PATH'
    }
    stages{
        stage ('Maven'){
            steps{
                echo "***** Maven Version *****"
                sh 'mvn --version'
            }
        }
        stage ('SpecificStage'){
            tools {
                jdk 'JDK-17'
            }
            steps {
                echo '****** Maven Version with m custom java at /opt******'
                sh "mvn --version"
            }
        }
    }
}
