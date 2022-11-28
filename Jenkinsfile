pipeline {
  agent any
     parameters {
        file(name: 'manifest.yml', description: 'Upload file test')
    }
  stages {
    stage('Example') {
      steps {
     script{
	    def  devdata = readYaml file: 'manifest.yml'
             echo "= = = = "
	     echo "${Environment}"
	     echo "Environment is ${devdata.Environment}"
       }
      }
    }
      
      
    }
  }

