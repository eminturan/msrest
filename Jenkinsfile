pipeline
{
    agent any
    tools
    {
        maven 'M3'
    }
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
