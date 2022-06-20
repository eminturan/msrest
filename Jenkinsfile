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
