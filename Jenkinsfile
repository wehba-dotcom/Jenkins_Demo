pipeline
{
    agent any 
    triggers
    {
       pollSCM("* * * * *")
    }
    stages
    {
     stage("build")
        {
                
         steps
            {
            bat "docker compose build"
            }
        }
        
    
    }
    
}
