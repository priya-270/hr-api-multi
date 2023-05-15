pipeline{
    agent any
    stages{
        stage("Git Checkout"){
            steps{
                git url:"https://github.com/priya-270/hr-api-multi"
            }
        }
         stage("Maven Build"){
            steps{
                sh "mvn clean package"
            }
        }
         stage("Dev Deploy"){
            steps{
                echo "deploying to dev environment"
            }
        }
    }
}