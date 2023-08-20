pipeline {
    agent any
    environment {
        //be sure to replace "bhavukm" with your own Docker Hub username
        //DOCKER_IMAGE_NAME = "SavithaRajakumar/train-schedule"
    }
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
      
       
 
        
      

    }
}
