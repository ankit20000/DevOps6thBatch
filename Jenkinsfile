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
       node ('kishore') 

    {
     echo "Deployment  has been started " 
        
    }
}
    } 
    
}  
    
}
