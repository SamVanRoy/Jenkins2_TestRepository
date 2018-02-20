pipeline {
    agent any
    parameters {
            string(name: 'Naampie', defaultValue: 'Sam', description: 'Wat is mijn naam?')
        }
    stages {
        stage('Example') {
                    steps {
                        echo "Hello ${params.Naampie}!"
                    }
                }
    }
}