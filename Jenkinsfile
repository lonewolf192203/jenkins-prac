pipeline{
    agent any
    stages{
        stage ("stage1") {
            steps{
                retry(3){ 
                     echo "hello ramu"
                     error "this is an error code"
                }
            }
        }
    }
}
