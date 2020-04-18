pipeline {
    agent any 
	triggers {
	    pollSCM('H/5 * * * *')
		}
		tools {
		 jdk 'JDK'
		 }
		 stages {
		   stage('Prepare the flow') {
		    steps {
			echo 'Hi Prepare flow'
			}
			}
			stage('Test our code') {
			steps {
			   echo 'Hi Test our code'
			   }
			}
			stage('Build code') {
			steps {
			   echo 'Hi Build our code'
			   }
			}
			stage('Deploy code') {
			steps {
			   echo 'Hi Deploy our code'
			   }
			}
		}
	}
