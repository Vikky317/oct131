pipeline {
    agent any
    tools {
      maven 'Maven1'
    }  
    stages{
        stage('Build') {
            steps{
                sh 'mvn clean package'               
            }          
        }  
     }
}
