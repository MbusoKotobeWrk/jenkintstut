//Jenkinsfile (Declarative Pipeline)
/*Requires the Docker Pipeline plugins*/
pipeline 
{
    agent 
	{
        docker 
		{
            image 'maven:3.9.0-eclipse-temurin-11'
        }
    }

    stages
	{
        stage('build') 
		{
            steps 
			{
                sh 'mvn -version'
            }
    	}
	}
}
