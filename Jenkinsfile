pipeline {
  agent any
  parameters {
    base64File 'yamlFile'
  }
  stages {
    stage('Example') {
      steps {
        withFileParameter('yamlFile') {
          def configVal = readYaml file: manifest.yml
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
