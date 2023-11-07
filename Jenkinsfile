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
        stage("buildDB")
        {
            steps
            {
                bat"docker compose build cache-db"
            }
        }
        
    
    }
    
}
