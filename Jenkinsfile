pipeline {
    
agent any 
  tools{
        maven 'maven_3_5_0'
    }
stages {
    stage("Check out and Build") {
     steps{
        git branch: 'main', url: 'https://github.com/wasimchoudhari/DevOps_project1'
        sh 'maven clean install'
    }
    }
}
}
