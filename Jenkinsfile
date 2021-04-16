node {
	checkout scm
	docker.wthRegistry('https://registry.hub.docker.com','dockerhub'){
		def customImage = docker.build("python_flask${env.BUILD}")
		customImage.push()
			
	}
	
}