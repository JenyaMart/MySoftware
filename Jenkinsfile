properties(
    [
        pipelineTriggers([pollSCM('H/30 * * * *')])
    ]
)
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
