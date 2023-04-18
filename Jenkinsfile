

pipeline{

    agent any

    
    stages{
         
        stage('Git Checkout'){
                    
            steps{

                scripts{

                  git branch: 'main', credentialsId: 'b4a9163c-7428-42b1-a2d6-9230a2d34f59', url: 'https://github.com/udhayacloud/aws.git'
                }

            
            }
        }
         
              