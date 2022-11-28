pipeline {
  agent any
  parameters {
    base64File 'manifest.yml'
  }
  stages {
    stage('Example') {
      steps {
     script{
        //withFileParameter('manifest.yml') {
          def configVal = readYaml file: manifest.yml
	   def devdata = readYaml file: 'manifest.yml'
            def env =devdata.Environment
	    
	    echo env
       }
      }
    }
      
    stage('deploy') {
      steps {
	    
        echo  "${Environment}"
          echo "${ArtifcatFile}"
	      }
        }  
      }
      
    }
  }
