pipeline{
    agent any
     stages{
         stage('first-build'){
             steps{
               sh "echo test stage; pwd; hostname"   
             
             stage('github-repo'){
                 steps{
                 git branch: 'main', url: 'https://github.com/Syedmanal/repo.git'
                 }
               }
             }
         }
     }
}
