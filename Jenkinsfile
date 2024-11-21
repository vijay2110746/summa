   pipeline {
       agent any
       stages {
           stage('Clone Repository') {
               steps {
                   git 'https://github.com/your-repo/my_python_app.git'
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
