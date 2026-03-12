pipeline{
  agent any
    stages{
      stage('Checkout'){
        steps{
          git 'https://github.com/asdfbytes/MyGitProject.git'
        }
      }
      stage('Publish'){
        steps{
          publishHTML([allowMissing:true, alwaysLinkToLastBuild:false, keepAll:false, reportDir:'.', reportFiles:'test.html', reportName:'Report'])

}
}
}
}
