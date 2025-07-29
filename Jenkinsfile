pipeline{
    agent any
    stages{
        stage ("1st stage"){
        steps {
            
            echo "hello anunay"
            sh "hostname -i"
             }
        }
         
        
        stage ("2nd stage"){
            agent{
                label 'java-node'
            }
             steps {
            echo "hello hey"
            sh "hostname -i"
            }
         }
        }
    }
