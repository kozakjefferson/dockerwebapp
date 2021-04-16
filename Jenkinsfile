node {
	checkout scm
	docker.withRegistry('https://registry.hub.docker.com','dockerhub'){
		def customImage = docker.build("jeffersonkozak/dockerwebapp")
		customImage.push()
			
	}
	
}
