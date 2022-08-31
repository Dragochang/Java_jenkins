pipeline {
    agent any
    //triggers {
		//cron('* * * * *')
	//}
    stages { 
	stage('Build') {
	    steps {
                      sh 'mvn clean install'	
		      echo 'building the application'
	    }
	}
	
	stage('Test') {
	    steps {
			      
			echo 'testing the application'
	    }
        }
		
	stage('Deploy') {
	    steps {
			      
			echo 'deploying the the application'
	    }
        }
    }
	
}
