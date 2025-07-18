pipeline{
    agent any
    stages{
        stage ("1st stage"){
        steps {
            
            echo "hello anunay"
            sh "hostname -i"
             }
        }
        stage ("groovy"){
             steps {
            def name = "sai"
            println("thanks you ${name}")
            }
         }
        }
    }
