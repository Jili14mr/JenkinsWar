pipeline {
  agent any
  stages {
    stage('Example') {
      steps {
     script{
      
          
	   def devdata = readYaml file: 'manifest.yml'
             echo "= = = = "
	     echo "Environment is ${devdata.Environment}"
       }
      }
    }
      
      
    }
  }

