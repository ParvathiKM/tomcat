pipeline {
    agent any
  
    stages{
        stage("clone git repo") {
            steps {
                script {

                    git credentialsId: 'git', url: 'https://gitlab.com/devopsuploads/devops.git'
                }
            }

        }
    }
  
}
  
