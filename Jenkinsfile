pipeline {
  agent any
     
  stages {
    stage('Example') {
      steps {
     script{
	     def yamlFile = readTrusted("config.yaml")
	     env.environment = conf.environment
	   // def  devdata = readYaml file: 'manifest.yml'
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

