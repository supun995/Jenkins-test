pipeline {
    agent any
    parameters { 
        string(name:"Greeting",defaultValue:"Hello",description:"ENter")
    }
    stages {
        stage('build') {
            steps {
                echo 'Hello World webhook'
                echo "${params.Greeting}"
            }
        }
    }
}
