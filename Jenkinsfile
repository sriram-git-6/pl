pipeline
{
    agent any
    stages
    {
        stage('ContinuousDownload')
        {
            steps
            {
                https://github.com/sriram-git-6/pl.git            }
            }
	 }   
        stage('ContinuousBuild')
        {
            steps
            {
                sh 'mvn package'
            }
        }
       
      }
    }  
