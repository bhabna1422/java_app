@Library('my-shared-lib') _

pipeline{
    agent any
    stages{
        stage('Git Checkout'){
            steps{
                scripts{
                 
                  gitCheckout{
                    branch: "main"
                    url: "https://github.com/bhabna1422/java_app.git"
                  }
                }
            }
        }
    }

}
