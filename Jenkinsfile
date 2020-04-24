pipeline{
    agent any
    stages{
        stage('Build Application'){
            steps {
                sh 'echo mvn clean package'
            }
            post {
                success {
                       echo "now archieving the artifact"
                      // archiveArtifacts artifacts: '**/*.war'}}
    }
   }
  }
