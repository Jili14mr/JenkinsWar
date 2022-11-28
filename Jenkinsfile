pipeline {
  agent any
  stages {
    stage('Example') {
      steps {
     script{
      
          def configVal = readYaml file: manifest.yml
	   def devdata = readYaml file: 'manifest.yml'
            def env =devdata.Environment
	    
	    echo env
       }
      }
    }
      
      
    }
  }

