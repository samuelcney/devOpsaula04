pipeline {
    agent any

    environment {
          MY_ENV_TEST = 'top10variaveisdeambiente'
        }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
  
        stage('Deploy') {
            steps {
                echo 'Deploying....'
		sh "echo Teste para printar Env: $MY_ENV_TEST"
            }
        }

        stage('Pitagoras') {
            steps {
                echo 'Pitagoras teve a casa alagada e o guarda roupa quebrou a porta....'
            }
        }

    }
}
