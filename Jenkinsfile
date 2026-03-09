pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/MohitBhasin17/javarep'
            }
        }
        stage('Publish') {
            steps {
                publishHTML([
                    allowMissing: true,
                    alwaysLinkToLastBuild: false,
                    keepAll: false,
                    reportDir: '.',
                    reportFiles: 'index.html',
                    reportName: 'MY HTML PAGE'
                ])
            }
        }
    }
}
