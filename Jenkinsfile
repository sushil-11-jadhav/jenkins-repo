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
                    sh "yum install maven -y"
                    sh 'mvn clean install'
                }
            
        }  
        }
}
