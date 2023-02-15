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
               sh 'touch newfile.txt'
               sh 'echo "newfile.txt created"'
               sh 'mv newfile.txt pipelineDocument.txt'
               sh 'echo ".txt Document renamed"'
               sh "pwd" 
            }
        }
    }
}
        
