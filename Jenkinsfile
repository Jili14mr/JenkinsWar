pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo "maven build"
                sh 'mvn clean install'
            }
        }

	    stage("Read Manifest Config") {
	        steps {
		        def configVal = readYaml file: "manifest.yml"
		        echo "configVal: " + configVal
	}
}
    }
}
