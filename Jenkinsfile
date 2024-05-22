pipeline { 
    agent {
        label "ws"
    }
    stages {
        stage('Lint Checks') {
            steps {
                sh "echo ***** Starting Style checks *******"
                // sh "mvn checkstyle:check || true"
                sh "echo **** Starting Style checks *******"
            }
        }
        stage('Static Code Analysis') {
            steps {
                sh "echo Starting Static code analysis"
            }
        }
    }
}