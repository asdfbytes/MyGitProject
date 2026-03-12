pipeline{
  agent any
    stages{
      stage('Checkout'){
        steps{
          git 'https://github.com/MCA104/HTML_FileWaalaRepo'
        }
      }
      stage('Publish'){
        steps{
          publishHTML([allowMissing:true, alwaysLinkToLastBuild:false, keepAll:false, reportDir:'.', reportFiles:'test.html', reportName:'Report'])

}
}
}
}
