pipeline {
    agent any
    stages {
        stage('git repo & clean') {
            steps {
//               sh "rm -rf csv-to-influxdb"
              sh "git clone https://github.com/safdarrizvi/csv-to-influxdb.git/"
            }
        }        
    }
}
