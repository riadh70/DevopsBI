pipeline { 
   
    agent any
    stages {  
       stage("Cloning Project"){
           steps {
            git branch: 'master',
            url: 'https://github.com/riadh70/Devops_Project.git'
            echo 'checkout stage'
            }
       } 
       
       stage ('MVN clean') {
         steps {
            sh 'mvn clean -e'
            echo 'Build stage done'
        }
     }
