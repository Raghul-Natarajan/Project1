pipeline{
    agent { label 'slave1' }
    stages {
        stage("Go-app"){
            
            steps{
               
               sh '''
                   echo $PATH
                   go version
                   go run main.go
                  '''
            }
        }
    }
}
