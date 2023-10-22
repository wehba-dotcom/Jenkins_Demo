pipeline
 {
agent any
triggers{
pollSCM(" * * * * * ")
}

stages{
  stage("build")
   {
    steps{
        sh "docker compose build "
         }
   }
    stage("build DivisorCounter")
   {
    steps{
        sh "docker compose up build DivisorCounter"
         }
   }
   }  
 }


