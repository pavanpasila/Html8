pipeline {
 agent any 
  
  stages {
    stage ("scm") {
      steps {
        git credentialsId: 'api-token', url: 'https://github.com/pavanpasila/Test-Repo.git'
      }
    }
  }
}
