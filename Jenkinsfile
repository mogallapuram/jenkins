pipeline    {
    agent{
        label 'agent1'
    }
    stages{
        stage('Build'){
            steps {
                sh 'echo this is build'
            }
        }
        stage('Test'){
            steps {
                sh 'echo this is test'
            }
        }
        stage('deploy'){
            steps {
                sh 'echo this is deploy'
            }
        }
    }
}