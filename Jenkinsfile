
stage("Read Manifest Config") {
	node {
		def configVal = readYaml file: "manifest.yml"
		//echo "configVal: " + configVal
		env.ArtifcatFile  = configVal['env']['name'][0]
		
		//ArtifcatFile = configVal['env']
		          echo "====="
		echo "${ArtifcatFile}"
		          echo "====="
		
		//env.test = configVal['BUILD']['test'][0]
                //env.SET = configVal['environment']
		
		//env.ArtifcatFile = configVal['environment']['name'][0]
		//env.STACK = configVal['applications']['stack'][0]
		//env.BUILD_PACK = configVal['applications']['buildpacks'][0][0]
	}
}


		         
			


