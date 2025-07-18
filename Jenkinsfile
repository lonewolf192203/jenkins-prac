pipeline{
    agent any
    stages{
        stage ("stage1") {
            steps{
                retry{ 
                     echo "hello ramu"
                     error "this is an error code"
                }
            }
        }
    }
}
