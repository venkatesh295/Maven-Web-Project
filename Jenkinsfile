#!groovy

node {
	   
	stage('Checkout'){

          checkout scm
       }

       stage('Compiling'){

          batfile 'mvn install'
       }
	   
      stage('Sonar') {
                    //add stage sonar
                    sh 'mvn sonar:sonar'
                }
       
}
