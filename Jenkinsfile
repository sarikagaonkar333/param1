pipeline {

agent any
    
stages {

  stage ('stage1'){
    steps{
      echo "stage 1 step "
      powershell returnStatus: true, script: '.\\Checkingservice.ps1'
    }

  }

  stage ('stage 2'){
    steps{
      echo "stage 2 step changes "
      powershell returnStatus: true, script: '.\\Addition.ps1'
    }

  }

}
}
