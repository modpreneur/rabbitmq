pipeline {
    agent {
        dockerfile {
             args '-p 15679:15672 -p 5679:15672'
        }

    }

    options {


    }

    stages {
        stage('Example') {
            steps {
                 echo 'Hello, RabbitMQ'
                 sh 'rabbitmq-server'
            }
        }
    }
}