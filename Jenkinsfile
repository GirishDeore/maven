pipeline{
    agent any
    stages{
        stage('Build Application'){
            steps {
                sh 'mvn clean package'
            }
            post {
            success {
            echo "now archieving the artifact"
            archiveArtifacts artifacts: **/*.war'}}
    }
   }
  }
