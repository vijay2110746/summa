   pipeline {
       agent any
       stages {
           stage('Clone Repository') {
               steps {
                   git 'https://github.com/vijay2110746/summa.git'
               }
           }
           stage('Install Dependencies') {
               steps {
                   sh 'pip install -r requirements.txt'
               }
           }
           stage('Run Tests') {
               steps {
                   sh 'pytest'
               }
           }
       }
   }
