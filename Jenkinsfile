node {
  stage('checkout'){
    checkout([$class:'GitSCM',branches: [[name:'*/main']], extensions: [],userRemoteConfigs: [[url:'https://github.com/sarishbosekar277/account-service']]])
  }
}
