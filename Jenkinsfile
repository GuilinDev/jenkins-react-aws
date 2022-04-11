pipeline {
     agent any
     stages {
        stage("Build") {
            steps {
                echo "Inside Build 1"
                // sh "sudo npm install"
                // sh "sudo npm run build"
            }
        }
        stage("Deploy") {
            steps {
                echo "Inside Deploy 2"
                // sh "sudo rm -rf /var/www/jenkins-react-aws"
                // sh "sudo cp -r ${WORKSPACE}/build/ /var/www/jenkins-react-aws/"
            }
        }
    }
}
