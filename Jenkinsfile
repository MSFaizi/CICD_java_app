pipeline{
  agent any

  stages{

    stage('Git Checkout'){

        steps{
            gitCheckout(
              branch: "main",
              url: "https://github.com/MSFaizi/CICD_java_app.git"
            )
        }
    }
  }
}