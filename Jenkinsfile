pipeline{
    agent{
        label "docker-linex"
    }
    stages{
        stage("Build"){
            
            steps{
                echo "nice to see you"
                sh 'mvn -B clean verify'
            }
        }
    }
}