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
            agent{
                label 'java-21'
            }
             steps {
            def name = "sai"
            println(thanks you ${name})
            }
         }
        }
    }
