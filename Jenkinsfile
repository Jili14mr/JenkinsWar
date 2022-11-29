
stage("Read Manifest Config") {
	node {
		def configVal = readYaml file: "manifest.yml"
		//echo "configVal: " + configVal
		
		env.ArtifcatFile = configVal['environment']
		//env.test = configVal['BUILD']['test'][0]
                //env.SET = configVal['environment']
		
		//env.ArtifcatFile = configVal['environment']['name'][0]
		//env.STACK = configVal['applications']['stack'][0]
		//env.BUILD_PACK = configVal['applications']['buildpacks'][0][0]
	}
}

stage("Deploy") {
	node {
                    echo "====="
			 echo "${ArtifcatFile}"
		         //echo "${test}"
			
		
	}
}
