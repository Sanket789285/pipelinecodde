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
    post{
        always{
            sh 'echo "always"'
        }
        success{
            sh 'echo "build success"'
        }
        failure{
            sh 'echo "failure"'
        }
    }
}