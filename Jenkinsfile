node {
  datas = readYaml file: 'release.yml'
  def mvnHome
    stage('Preparation') { // for display purposes
        // Get some code from a GitHub repository
        git 'https://github.com/jglick/simple-maven-project-with-tests.git'
        // Get the Maven tool.
        // ** NOTE: This 'M3' Maven tool must be configured
        // **       in the global configuration.
        mvnHome = tool '3.5.4'
    }
    stage('Build') {
        // Run the maven build
        
      sh "$mvnHome clean install"
        
        }
    
  
}
