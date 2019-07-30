pipeline {

	agent none

	

	environment {
	    MyKeyID="myCustomValue1"
	}
	
	stages {

	stage('Descargar codigo fuente') {
		environment {
	    MyKeyID="myCustomValue2x"
	}
    	steps {
    		script {
          		node {
        				println " Mi primer stage.\n MyKeyID value es: ${MyKeyID}"
          		}
        	}
    	}
	} 
	
	
}
}