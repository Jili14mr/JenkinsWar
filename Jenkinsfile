...

stage("Read Manifest Config") {
	node {
		def configVal = readYaml file: "manifest.yml"
		echo "configVal: " + configVal
		
		env.ArtifcatFile = configVal['environment']['name'][0]
		//env.STACK = configVal['applications']['stack'][0]
		//env.BUILD_PACK = configVal['applications']['buildpacks'][0][0]
	}
}

stage("Deploy") {
	node {
		sh '''
			...
			
			 echo ${APP_NAME} 
			
			...		
		'''
	}
}
