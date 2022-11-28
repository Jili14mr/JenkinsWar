pipeline {
    agent any

    stages {
	    
	    
	//stage("Read Manifest Config") {
	    //steps {
		  //  def configVal = readYaml file: "manifest.yml"
		   // echo "configVal: " + configVal
	   // }
	//}

		    
        stage('build') {
            steps {
                echo "maven build"
		   // echo  "${Environment}"
		   // echo "${ArtifcatFile}"
                sh 'maven clean install'
            }
        }

    }
}
