pipeline {	
    agent{
        dockerfile{
            label 'slave'
        }
    }
    stages {	
        stage('Build') {	
            steps {	
                sleep(time: 10, unit: 'SECONDS') 	
                echo 'Hello World 7'	
            }	
        }	
    }	
}	
