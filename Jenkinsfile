pipeline {
  agent any
     
  stages {
    stage('Example') {
      steps {
     script{
	    def  devdata = readYaml file: 'template.yaml'
             echo "= = = = "
	     echo "Hello ${aParam}"
	     //echo ${devdata.ArtifcatFile}
	     //echo "${Environment}"
	     echo "Environment is ${devdata.Environment}"
       }
      }
    }
      
      
    }
  }

