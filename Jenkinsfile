pipeline {

    agent any

  
    stages {
        stage('Jmeter') {
            steps {
                {
                 sh 'mvn verify -Pperformance'
                }
            }
        }
    }    
}
