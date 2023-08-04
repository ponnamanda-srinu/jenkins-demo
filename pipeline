def GIT_CREDENTIALS= "gitcredentials"
pipeline{
    agent any
    stages{
        stage('checkout code'){
            steps{
                script{
                    git credentialsId: GIT_CREDENTIALS,
                    url:"https://github.com/ponnamanda-srinu/jenkins-demo.git", branch: "main"
                }
            }
        }
        stage('maven'){
            steps{
                echo "/opt/maven"
            }
        }
        stage('tomcat'){
            steps{
                echo "/opt/tomcat"
            }
        }
        stage('deploye'){
            steps{
                echo "deploye"
            }
        }
    }
}