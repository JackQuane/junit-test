pipeline{
    agent any
    stages{
        stage('--Clean--'){
            steps{
                sh "mvn clean"
            }
        }
        stage('--Test--'){
            steps{
                sh "mvn test"
            }
        }
        stage('--Depoly--'){
            steps{
                sh "mvn package"
            }
        }
    }
}
