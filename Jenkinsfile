pipeline{
    agent docker {
        image 'maven:3-alpine'
        label 'my-defined-label'
        args  '-v /tmp:/tmp'
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