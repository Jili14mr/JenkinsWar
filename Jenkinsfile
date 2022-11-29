stages {
    stage('Read YAML file') {
      steps {
        script {
          def datas = readYaml file: 'release.yml'
          echo "Got version as ${datas.first} "
        }
      }
    }
}

