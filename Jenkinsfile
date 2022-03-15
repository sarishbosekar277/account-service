node {
  stage('checkout'){
    checkoutcheckout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/sarishbosekar277/account-service']]])
  }
}
