pipeline {
    agent { label 'docker-slave-agent' } 
	
    stages {
	 
	    
        stage('App') {
		
            steps {
                sh '''
        git clean -fdx  //clean before checkout
    	docker-compose --version
        docker-compose up -d --force-recreate
	
	
	'''
	
            }
        }
	 	    
    }
}
