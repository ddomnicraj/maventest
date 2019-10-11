node{
  stage{ 'SCM Checkout' }{
    git 'https://github.com/ddomnicraj/maventest/new/master'
  }
  stage{ 'Complile the code' }{
    def defaultmaven = tool name: 'defaultmaven', type: 'maven'
    sh 'mvn package'
  }
}
