pipeline{
    agent any
    tools{
        maven 'maven'
    }
    stages{
        stage('git checkout'){
            steps{
                git 'https://github.com/project332/java-tomcat-maven-example.git'
            }
        }
    }
}
