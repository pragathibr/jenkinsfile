pipeline {
   agent any
   stages {
      stage("Compilation") {
         steps {
               echo "This is compilation"
            } 
      }
      stage("Testing") {
         steps {
            echo "This is testing"
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
