pipeline {
  agent any
  stages {
    stage('Read YAML file') {
      steps {
        script {
          def datas = readYaml file: 'release.yml'
          def name = "${datas.first}"
          echo "Got version as ${name}"
          //echo "Got version as ${datas.second} "
          
        }
      }
    }
    
}
}
