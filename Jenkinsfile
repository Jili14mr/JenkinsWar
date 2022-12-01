pipeline {
  agent any
  stages {
    stage('Read YAML file') {
      steps {
        script {
          def datas = readYaml file: 'release.yml'
          echo "Got version as ${datas.first} "
          echo "Got version as ${datas.second} "
          
        }
      }
    }
     stage('Printing name') {
            steps {
                script {
                    def name = "${datas.first}"
                    def gender = "${datas.second}"
                  echo "${gender}"
                  
      }
    }
  }
}
}
