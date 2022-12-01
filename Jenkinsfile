node {
  datas = readYaml file: 'release.yml'
}
pipeline {
  stage ('Build') {
    git url: 'https://github.com/Jili14mr/JenkinsWar.git'
    withMaven {
      sh "mvn clean install"
      echo "Got version as ${datas.first} "
    }
  }
}
