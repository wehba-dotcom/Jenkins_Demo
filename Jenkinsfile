pipeline
{
    agent any 
    triggers{
    pollSCM("* * * * *")
    }
    stages{
    stage("build")
    {
        steps{
     sh "docker compose build"
    }
    }
   stage("buildservice"){
    steps{
        sh "docker compose up counter-service"
    }
   }
    }
    
}
