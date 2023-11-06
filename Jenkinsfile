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
    stage("buildService")
    {
    steps{
        sh"docker compose up DivisorCounter" 
    }
    }
    }
    
}
