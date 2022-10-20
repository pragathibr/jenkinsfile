pipeline {
   agent any
   stages {
      stage("Compile this project") {
         steps {
               echo "This is compilation"
            } 
      }
      stage("Testing") {
         steps {
            sh "This is testing"
         }
      }
       stage("Packaging") {
          steps {
            echo "This is packaging"
         }
      }       
   }
   post {
      success {
         echo "Ths is success job"
      }
      failure {
         echo "This is failure job"
      }
   }
}
