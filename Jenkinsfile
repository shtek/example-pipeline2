pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!'
               
                echo currentBuild.projectName
                echo  "${BUILD_URL}" 
                echo env.JENKINS_URL
                echo 'hello again'
                
            }
        }
        
    }
}
