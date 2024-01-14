pipeline{

    agent any

    stages{
        stage("compile"){
            steps{
                 sh 'javac test.java'
            }
           
        }

        stage("run"){
            steps{
                 sh "java test"
            }
           
        }
    }
}