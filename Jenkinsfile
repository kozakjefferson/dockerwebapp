node {
	checkout scm
	docker.withRegistry('https://registry.hub.docker.com','dockerhub'){
		def customImage = docker.build("python_flask${env.BUILD}")
		customImage.push()
			
	}
	
}
