pipeline {
    agent any  // You can specify a specific agent to run the pipeline on

    stages {
        stage('first') {
            steps {
                // Check out your source code repository here (e.g., Git)
                // Example: git 'https://github.com/your/repository.git'
            
            echo "This is the first stage"

            }
        }

        stage('Second') {
            steps {
                // Execute your build steps here
                // Example: sh 'mvn clean install'

                    echo "This is the second stage"


            }
        }

        stage('Third') {
            steps {
                // Execute your test steps here
                // Example: sh 'mvn test'
              echo "This is the Third  stage"

            }
        }

        stage('Fourth') {
            steps {
                // Execute deployment steps here
                // Example: sh 'docker-compose up -d'

                 echo "This is the fourth stage"
            }
        }
    }

}
