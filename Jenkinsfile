pipeline {
    agent any
    parameters {
            string(name: 'Naampie', defaultValue: 'Sam', description: 'Wat is mijn naam?')
        }
    stages {
        stage('Build') {
                        steps {
                            echo "Running ${env.BUILD_ID}"
                        }
            }
        stage('Test') {
                    steps {
                        echo "Hello ${params.Naampie}!"
                    }
            }
    }
}