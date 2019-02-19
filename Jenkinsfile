pipeline{
    agent{
        label "docker-linex"
    }
    stages{
        stage("Build"){
            agent { docker 'maven:3-alpine' }
            steps{
                echo "nice to see you"
                sh 'mvn -B clean verify'
            }
        }
    }
}