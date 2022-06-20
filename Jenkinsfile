pipeline
{
    agent any
    stages
    {
        stage('Build Jar')
        {
            steps
            {
                echo "maven stage"
                archiveArtifacts artifacts: '*'
                sh "ls"
            }
        }
        stage('Build Docker Image')
        {
            steps
            {
                script
                {
                    echo "docker stage"
                }
            }
        }
    }
}
