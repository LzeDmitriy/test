pipeline {
    agent any

    environment {
        PROJECT_NAME = 'Learning of Jenkins'
        MAINTAINER_NAME = 'Seregin Dmitiriy'
    }

    stages{
        stage('1-Build'){
            steps{
                echo 'Start Build'
                echo 'Building....'
                echo "End of Build"
            }
        }
        stage('2-Testing'){
            steps{
                echo 'Start Test'
                echo 'Testing....'
                echo "Privet ${PROJECT_NAME}"
                echo "Owner is ${MAINTAINER_NAME}"
                echo "End of Test"  
            }
        }
        stage('3-Deploy'){
            steps{
                echo 'Start Deploy'
                echo 'Deploying....'
                echo "End of Deploy"  
            }
        }        
    }
}
