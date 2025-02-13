pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh '''
                    echo 'hi there'
                    ctest -T test --output-junit TestResults.xml
                '''
            }
        }

    // }

    // post {
    //     always {
    //         archiveArtifacts artifacts: 'build/libs/**/*.jar', fingerprint: true
    //         junit 'build/reports/**/*.xml'
    //     }
    }
    }
