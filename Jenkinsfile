pipeline{
    agent { label 'slave1' }
    stages {
        stage("Go-app"){
            
            steps{
               
               sh 'go run main.go'
            }
        }
    }
}
