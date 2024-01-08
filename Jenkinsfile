@Library('my_shared_library') _

pipeline {

    agent any

    stages{

        stage('git checkout') {

            steps{

                script {

                    gitCheckout (
                        branch:"test" ,
                        url:"https://github.com/Ravi4410/Project-java.git"
                    )
                    
                }

            }


        }


    }
    
}