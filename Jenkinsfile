@Library("my-shared-library")_
pipeline{

    agent any

    
    stages{
         
        stage('Git Checkout'){
            steps{

                script{
                    gitCheckout(
                        branch: 'main',
                        url: 'https://github.com/chuksdsilent/devops_java_app.git'
                    )
                }
            }
        }
    }
}