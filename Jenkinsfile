pipeline{
    agent any
    stages{
        stage("SCM Code"){
            steps{
                git branch:'master',
                credentialsId:'github',
                url:'https://github.com/Amarnatha899/practice.git'
            }
        }
    }
}
