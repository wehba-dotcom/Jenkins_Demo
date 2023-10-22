pipeline
{
    agent any 
    Triggers{
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
