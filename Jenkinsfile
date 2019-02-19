pipeline{
    agent { docker 'maven:3-alpine' }
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