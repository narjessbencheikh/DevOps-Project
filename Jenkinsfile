pipeline {
    agent any
    stages {

        stage('Print') {
            steps {
                script {
                    def now = new Date()
                    date = now.format("yyyy-MM-dd", TimeZone.getTimeZone('UTC'))
                    echo "Current date : ${date}."
                }
            }
        }


        
    }
}
