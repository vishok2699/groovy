#!/usr/bin/env groovy
pipeline {
    agent{ label 'master' }
stages{
    stage('QA'){
        steps{
            script{
                echo "inside QA"
                sh '/home/vishok/Downloads/shell.sh $Name $LastName'
            }
        }
    
    }
    stage('stable'){ 
        steps {
            script{
                echo "inside stable"
                echo "inside GROOVY $Name"
            }
            }
        
    }

}
}
