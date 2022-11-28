pipeline {
  agent any
     
  stages {
    stage('Example') {
      steps {
     script{
	    def  devdata = readYaml file: 'manifest.yml'
             echo "= = = = "
	     echo ${devdata.ArtifcatFile}
	     echo "${Environment}"
	     echo "Environment is ${devdata.Environment}"
       }
      }
    }
      
      
    }
  }

