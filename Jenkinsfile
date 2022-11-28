pipeline {
  agent any
  parameters {
    base64File 'manifest.yml'
  }
  stages {
    stage('Example') {
      steps {
        withFileParameter('manifest.yml') {
         // def configVal = readYaml file: manifest.yml
	   def devdata = readYaml file: manifest.yml
        }
      }
    }
      
    stage('Example') {
      steps {
        echo  "${Environment}"
		    echo "${ArtifcatFile}"
        }
      }
      
    }
  }
