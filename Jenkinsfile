pipeline {
    agent none
stages{
    stage('QA'){
    agent { node { label 'master' } } 
        steps{
            script{
                echo "inside QA"
                'sh /home/vishok/shell.sh $Name $LastName'
            }
        }
    
    }
    stage('stable'){
    agent { node {label 'newnode'} } 
        steps {
            script{
                echo "inside stable"
                echo "inside GROOVY $Name"
            }
            }
        
    }

}
}
