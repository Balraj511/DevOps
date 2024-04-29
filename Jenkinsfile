pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Pull source code from GitHub repository
                git url: 'https://github.com/Balraj511/DevOps.git', branch: 'main'

                // Copy code to web server path
                sh 'sudo cp -r ./* /var/www/html/'
            }
        }

         stage('Get URL') {
            steps {
                // Retrieve the URL of your application
                // Replace this with the command to get the URL of your application
                 echo "http://13.51.175.88/index.html" 
            }
        }
    }
}
