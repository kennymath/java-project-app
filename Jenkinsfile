@Library('my-shared-library') _

pipeline{

    agent any

    stages{

        stage('Git Checkout'){

            steps{

                script{

                    gitCheckout(
                        branch: "main"
                        url: "https://github.com/kennymath/java-project-app.git"
                    )
                }
            }
        }
    }
}