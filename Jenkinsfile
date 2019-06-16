pipeline {
    agent any
    parameters {
        string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
        string(name: 'Fucking', defaultValue: 'Fucking', description: 'How should I Fucking the world?')
    }
    stages {
        stage('Example') {
            steps {
                echo "${params.Greeting} World!"
                echo "${params.Fucking} World!"
            }
        }
    }
}
