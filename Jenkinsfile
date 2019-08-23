pipeline {
	agent { label 'java' }
	stages {
	   stage ('Build') {
	   	  steps {
	   	  	withMaven() {
	   	  	    sh "./mvnw clear verify"
	   	  	}
	   	  }
	   }
	}
}