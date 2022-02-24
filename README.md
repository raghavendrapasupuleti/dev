pipeline{
    
    agrnt any 
    stages {
       stage ("build") {
            steps{
                echo " build"
            }       
       }
       stage ("deploy") {
           steps {
               echo "deploy"
           }
       }
   }
}
