pipeline {
	agent any
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