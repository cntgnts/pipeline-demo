
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script {
                   def kamal
                   kamal = load "kam.groovy" 
                   kamal.displaynames(10,20)
                   kamal.myjob("DevOps")
                }
            }
        }
    }
}
