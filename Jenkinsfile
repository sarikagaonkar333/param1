pipeline {

agent any
    
stages {

  stage ('stage 2'){
    steps{
      echo "stage 2 step changes "
      powershell returnStatus: true, script: '.\\Addition.ps1'
    }

  }

}
}
