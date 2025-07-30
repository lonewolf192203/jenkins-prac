pipeline{
    agent{
        label "java-node"
    }
    stages{
        stage('Build'){
            steps{
                echo('this is build stage')
            }
        }
        stage('deployment'){
            steps{
                echo('this is deployment stage')
        }
        }
        stage('Scans'){
            steps{
                echo('this is scan stage')
        }
    }
}
}
