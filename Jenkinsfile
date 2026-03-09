pipeline{
agent any

stages{
stage{'checkout'){

steps{
git 'https://github.com/MohitBhasin17/javarep'
}
}

      stage('Publish'){
        steps{
          publishHTML{[

            allowmissing:true,
            alwaysLinktoLastBuild:false,
            KeepAll:false,
            reportDir:'.',
            reportFiles:'index.html',
            reportName:'MY HTML PAGE
        ]
      }
   }
  }
