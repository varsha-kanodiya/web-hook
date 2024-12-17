pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
                 git 'https://github.com/Pritam-Khergade/student-ui.git'

            }
       
        }
   }      
  
}  
  
  
