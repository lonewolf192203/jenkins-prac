pipeline{
    agent{
        label "java-node"
    }

    tools{
        maven "maven-3.8.8"
    }

    stages{
        stage("maven"){
            steps{
                sh "java --version"
                sh "mvn --version"
            }
        }
    }
}
