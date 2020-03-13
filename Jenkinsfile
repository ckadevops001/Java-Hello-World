pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Java build automation'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/Java-Hello-World.zip'
            }
        }
    }
}
