pipeline{
    agent any
    
    tools{
        maven 'maven 3.8.8'
    }

    stages{
        stage("maven"){
            steps{
                sh "mvn --version"
            }
        }
        stage("diff maven"){
            tools{
                jdk 'JDK-17'
            }
                steps{
                sh "mvn --version"
            }
        }
    }
}
