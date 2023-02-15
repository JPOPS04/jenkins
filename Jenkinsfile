pipeline {
    agent any
    stages {
        stage('Pipeline Stages'){
            steps {
                sh "ls"
            }
        }
        stage('Stage2'){
            steps {
               sh "pwd"
            }
        }
        stage('Stage3'){
            steps {
               echo 'hello new'
            }
        }
        stage('Stage4'){
            steps {
               sh "touch newfile.txt"
            }
        }
        stage('Stage5'){
            steps {
               sh "mv newfile.txt"
            }
        }
    }
}
        
