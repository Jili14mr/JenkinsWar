node {  devdata = readYaml file: 'manifest.yml'
     }
pipeline {
  agent any
  stages {
    stage('Example') {
      steps {
     script{
             echo "= = = = "
	     echo "Environment is ${devdata.Environment}"
       }
      }
    }
      
      
    }
  }

