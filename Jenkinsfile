pipeline {
    agent any
stages {
        stage('git checkout') {
            steps{
                git branch: 'main', url: 'https://github.com/Sumeet-Anand12/dineshJenkins.git'
            }
            
        }
        stage('print data')
        {
            steps{
            echo "hello Dinesh"
            }
        }
    }
}
