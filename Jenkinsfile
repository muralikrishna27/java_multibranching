pipeline
{
    agent any
    stages
    {
        stage('ContDownload_Master')
        {
            steps
            {
                script
                {
                    cicd.newGit("maven")
                }
            }
        }
        stage('ContBuild_Master')
        {
            steps
            {
                script
                {
                    cicd.newBuild()
                }
            }
        }
    }
}
