//  trying the retry feature in jenkins file
// retry ===> multiple attempts
// timeout -===> time limit enforced

// pipeline for retry

pipeline {
    agent any
    stages{
        stage ('Build' ){
            steps {
                echo "******* Entering Build Block *******"
                retry (3) {
                    echo "welcome to D4"
                    error " Testing the retry block"
                }
                echo "******* After 3 retrys *******"   
            }
        }
    }

}
