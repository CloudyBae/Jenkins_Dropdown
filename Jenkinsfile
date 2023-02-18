pipeline {
    agent any

    parameters {
        choice(choices: ["TEST", "DEV", "QA", "PRE-PROD", "PROD"], description: "Which enviornment to deply in?", name: "deployEnv")
    }

    stages {
        stage("Demo"){
            steps {
                echo "choice is set to: ${params.deployEnv}"
            }
        }
    }
}