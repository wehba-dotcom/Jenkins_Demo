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
     sh "dotnet build DivisorCounter.csproj"
    }
    }
    }
    
}
