pipeline {
agent {
label 'K8S-MASTER '
}

stages {

stage ('Checkout') 
{
steps
    {
    
        checkout scm
        
    }
    
}
stage ('Build1') 
{
    steps
    {
      echo "Builing has been started " 
    }
}
    stage ('Test') 
{
    steps
    {
        echo "Testing has been started " 
    }
}
     stage ('Deployment ') 
{
    steps {
       node ('K8S-MASTER') 

    {
     echo "Deployment  has been started " 
        
    }
}
    } 
    
}  
    
}
