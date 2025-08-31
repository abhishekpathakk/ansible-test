pipeline {
    agent any

    stages {
        stage('Install netstat') {
            steps {
                sh '''
                ansible-playbook -i /home/abhishekpathak2905/hosts.ini /home/abhishekpathak2905/install_netstat.yml
                '''
            }
        }
    }
}
