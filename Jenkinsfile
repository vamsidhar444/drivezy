#!groovy

node {
	   
	stage('Checkout'){

          checkout scm
       }

       stage('BuildArtifact'){

         // bat 'mvn install'
	       
	     bat   'mvn package'
       }
	   
      
	
       
}
