node {
  def MAVEN_HOME = tool "mymaven"
   env.PATH = "${env.PATH}:${MAVEN_HOME}/bin"

  stage('checkout'){
    checkout([$class:'GitSCM',branches: [[name:'*/main']], extensions: [],userRemoteConfigs: [[url:'https://github.com/sarishbosekar277/account-service']]])
  }
  
    stage('initial set up'){
      sh 'mvn clean compile'
      stage('unit Testing'){
        sh 'mvn test'
  
  }
}
