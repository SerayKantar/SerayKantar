node{
  stage('SCM Checkout'){
    git 'https://github.com/SerayKantar/SerayKantar'
  }
  stage('Compile-Package'){
    // Get maven home path
   def M2_HOME = tool name: 'Maven', type: 'maven'
    sh ``${apache-maven-3.8.5}/bin/mvn package``
  }
  
}
