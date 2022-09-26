pipeline {
    agent any
    stages {
        stage('Checkout Git') {
            steps {
               echo 'Pulling...';
               git branch : 'main',
               url : 'https://github.com/narjessbencheikh/DevOps-Project';
            }
        }

        stage('Print') {
            steps {
                script {
                    def now = new Date()
                    dateRelease = now.format("yyyy-MM-dd", TimeZone.getTimeZone('UTC'))
                    echo "Current date ${dateRelease}."
                }
            }
        }


        
    }
