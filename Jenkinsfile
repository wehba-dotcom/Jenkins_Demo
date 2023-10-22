pipeline
{
    agent any 
    triggers{
    pollscm("*****")
    }
    stages{
    stage("build")
    {
        steps{
    sh "docker compose build "
    }
    }
    }
    
}
