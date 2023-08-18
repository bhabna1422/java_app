// @Library('my-shared-library@main') _

pipeline{
    agent any
    stages{
        stage('Git Checkout'){
            steps{
               script {
               git branch: 'main', url: 'https://github.com/bhabna1422/java_app.git'
                // gitCheckout{
                //     branch : "main"
                //     url: "https://github.com/bhabna1422/java_app.git"
                // }
               }
            }
        }

        stage('Unit test Maven'){
            steps{
               script {
                  sh 'mvn test'
                // echo "hello"
               }
            }
        }
    }

}
