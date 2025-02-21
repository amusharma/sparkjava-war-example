pipeline {
    agent any

    stages {
        stage ('git clone') {
            steps {

                git url: 'https://github.com/amusharma/sparkjava-war-example.git', branch: 'master'
            }

        }
        
        stage ('create package') {
            steps {
               
                sh 'mvn clean install'
            }


        }

    }

}
