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
    echo "====++++something++++==== docker compose build "
    }
    }
    }
    
}
