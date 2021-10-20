pipeline {
    agent any
    stages {
        
        stage('Pull Sources') {
            steps {
             git url: 'https://github.com/awstechguide/spring-webapp.git'
            }
         }
        
       
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
	}
      
    	}
    }    	    
