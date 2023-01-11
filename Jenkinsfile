pipeline {
agent any 
    
stages {
    stage("Check out and Build") {
     steps{
        checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/wasimchoudhari/DevOps_project1']])
     
    }
    }
}
}
