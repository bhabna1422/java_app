pipeline{
    agent any
    stages{
        stage('Git Checkout'){
            steps{
                scripts{
                 
                  gitCheckout{
                    branch: "master"
                    url: "https://github.com/bhabna1422/java_app.git"
                  }
                }
            }
        }
    }

}
