pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!'
                 echo params.PARAM1
                echo currentBuild.projectName
                echo  "${BUILD_URL}" 
                echo env.JENKINS_URL
                echo 'hello again'
                echo "current build ${currentBuild.number}"
                
            }
            post{
                success{
                    script{
                       currentBuild.result='FAILURE'
                    }
                }
            }
        }
        
    }
}
