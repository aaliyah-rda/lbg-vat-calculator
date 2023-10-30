pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        //Get some code from a Github repository
        git branch: 'main', url: 'https://github.com/aaliyah-rda/lbg-vat-calculator.git'
      }
    }
    stage('SonarQube Analysis') {
      environment {
        scannerHome = tool 'sonarqube'
      }
        steps {
          withSonarQubeEnv('sonar-qube-1-) {
            sh "${scannerHome}/bin/sonar-scanner"
                           }
                           }
                           }
                           }
                           }
      
  