node{
  stage('SCM Checkout'){
        git 'https://github.com/zemandic/my-app'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
  
}
