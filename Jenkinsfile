node {
  datas = readYaml file: 'release.yml'

  stage ('Build') {
    git url: 'https://github.com/Jili14mr/JenkinsWar.git'
    withMaven {
      sh "mvn clean install"
      echo "Got version as ${datas.first} "
    }
  }
 stage ('deplyment') {
  
   steps {
               
               
                
               sh echo "Got version as ${datas.first} "
               //sh " cd /var/lib/jenkins/workspace/${UAIName}-${AppName}-${Cluster}-${ArtifactName}-Buildjob"
               // cd target
               // ls -alt
                
 
}
}
