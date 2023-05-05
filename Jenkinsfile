pipeline {
    agent {
              label {
                label "slave"
                customWorkspace "/mnt/repo"
               }
    }
    stages {
        stage ('Stage1-slavejnlp') {
            
            steps {
                    sh 'mvn clean install'
                }
            
        }  
        }
}
