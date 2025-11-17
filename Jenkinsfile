pipeline {
    agent any

    stages {
        // stage('COnenct to git'){
        //     steps{
        //         git url: 'https://github.com/delfina-busigina/validate_report.git', credentialsId: 'pers_github_cred'
        //         echo 'initialized connection'
        //     }
        // }
        stage('Run Python Script') {
            steps {
                sh 'python3 main/hello.py'
            }
        }
    }
}