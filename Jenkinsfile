#!groovy

node {
	   
	stage('Checkout'){

          checkout scm
       }

       stage('Compiling'){

          bat 'mvn clean install'
       }
	   
      stage('Sonar') {
                    //add stage sonar
                    sh 'mvn sonar:sonar'
                }
       
}
