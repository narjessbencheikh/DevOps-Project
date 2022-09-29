pipeline {
    agent any
    stages {

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
}
