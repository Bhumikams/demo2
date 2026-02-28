pipeline {
  agent any

  stages {
    
    stage('Close') {
      steps {
        git url: 'https://github.com/Bhumikams/demo2.git',
          branch: 'main'
      }
    }

    stage('Run Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}    
