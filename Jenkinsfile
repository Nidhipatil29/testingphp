pipeline {
    agent any

    stages {
        stage('build') {
            steps {
               git url: 'https://github.com/Nidhipatil29/testingphp.git'
               sh 'ls -a'
               sh 'docker build -t myphpproject .'
            }
        }
    }
}
        
        /*stage('deploy') {
            steps {
              sh 'docker run --name mytestcontainer -itd -p 80:80 myphpproject'
            }
        }*/
