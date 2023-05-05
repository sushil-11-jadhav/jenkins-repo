pipeline {
    
    stages {
        stage ('Stage1-JM') {
            agent {
              label {
                label "built-in"
                customWorkspace "/mnt/repo"
               }
           }
            steps {
                
                    sh 'mvn clean install'
                }
            
        }  
        }
}
