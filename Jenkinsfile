pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!'
                env.MYTOOL_VERSION = '1.33'
                echo currentBuild.projectName
                echo env.MYTOOL_VERSION
                echo 'hello again'
                
            }
        }
        
    }
}
