pipeline {
    agent {
              label {
                label "built-in"
                customWorkspace "/mnt/repo"
               }
    }
    stages {
        stage ('Stage1-JM') {
            
            steps {
                
                    sh 'mvn clean install'
                }
            
        }  
        }
}
