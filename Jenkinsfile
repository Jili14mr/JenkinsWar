pipeline {
    agent any
    stages {
        stage('Stage1') {
            steps {
            script {
                   def datas = readYaml file: 'release.yml'
                   echo "Got version as ${datas.version} "
        }
        
    }

}
}
}
