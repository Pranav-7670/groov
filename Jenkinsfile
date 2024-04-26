pipeline{
    agent any 
    

    stages{
         
        stage('equal stage')
        { 
          when {
                  branch 'main'
            }
    
         steps{
                echo "i am from main branch"
                              
              }       
            
        }
       stage('not stage')
        { 
         when {
                 branch 'dev'
            }

         steps{
                echo "i am in branch dev"            
              }       
            
        }     

          }
}          
