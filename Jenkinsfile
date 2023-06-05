@Library('library')_
pipeline
{
   agent any
   stages
   { 
     stage('contDownload')
     {
      steps
      {
        script
	{
           cicd.newGit("maven")
	}
      }
     }
   }
}

