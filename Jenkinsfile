pipeline {
    agent { label 'docker-slave-agent' } 
	
    stages {
	 
	    
        stage('App') {
		
            steps {
                sh '''

    	docker-compose --version
        docker-compose up -d --force-recreate
	sudo chown -R jenkins:jenkins app/target 
	
	
	'''
	
            }
        }
	 	    
    }
}
