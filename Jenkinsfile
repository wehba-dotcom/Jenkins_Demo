pipeline
{
    agent any {
    Triggers{
    pollscm("*****")
    }
    stages{
    steps("build")
    {
    sh "dotnet build DivisorCounter.csproj "
    }

    }
    }
}
