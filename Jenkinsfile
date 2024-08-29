pipeline {
    agent any
    stages{
        stage('TimeoutStage'){
            steps {
                timeout(time:5, unit: 'SECONDS'){
                    echo "sleeping for 60 sec"
                    sleep 60
                   // manager approval
                
                }
            }
        }
    }
}
