pipeline {
    agent {
              label {
                label "slave ssh"
                customWorkspace "/mnt/repo"
               }
    }
    stages {
        stage ('Stage1-slavessh') {
            
            steps {
                    sh 'sudo mvn clean install'
                }
            
        }  
        }
}
