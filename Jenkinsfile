pipeline{
    agent { label 'slave1' }
    tools {
      Go '1.19.4'
   }
    stages {
        stage("Go-app"){
            
            steps{
               
               sh '''
                   echo $PATH
                   go version
                   hostname
                   go run main.go
                  '''
            }
        }
    }
}
