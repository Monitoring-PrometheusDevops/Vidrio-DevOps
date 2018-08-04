pipeline {	 
 	agent any
 	stages {
 	  stage('Checkout scm') { 
 	    steps {
 	      checkout scm
 	    }
 	  }
 	  stage('Build & Run') { 
 	    steps {
 	      ruby hello.rb
 	    }
 	  }
  }
}
