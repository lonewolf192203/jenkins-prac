pipeline{
    agent{
        label "java-node"
    }

    stages{
        stage("maven"){
                    tools{
                    maven '3.8.8'
                         }
            steps{
                sh "java --version"
                sh "mvn --version"
            }
        }
    }
}
