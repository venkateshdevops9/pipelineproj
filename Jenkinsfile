pipeline{
   agent any
   tools{
         jdk 'myjava'
         maven 'mymaven'
         }
   stages{
    
     stage ('git'){
     
      steps{

         git 'https://github.com/kliakos/sparkjava-war-example.git'
            }
                   }
     
      stage ('maven'){

      steps{

          sh 'clean package'
            }
                     }

         }
        }
