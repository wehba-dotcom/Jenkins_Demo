pipeline
{
    agent any {
    Triggers{
    pollscm("*****")
    }
    stages{
    steps("build")
    {
    sh "docker compose build "
    }

    }
    }
}
