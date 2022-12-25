pipeline{
    agent { label 'slave1' }
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
