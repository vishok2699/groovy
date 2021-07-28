#!/usr/bin/env groovy
pipeline {
    agent{ label 'master' }
stages{
    stage('QA'){
        steps{
            script{
                echo "inside QA"
                'sh /home/vishok/Downloads/shell.sh $Name $LastName'
            }
        }
    
    }

}
}
