pipeline {
    agent any
    stages {    
        stage("git checkout") {
            steps {    
                git 'https://github.com/hspijkerman/testpyramidexample.git'
            }
        }   
        stage(" change directory"){
            steps{
                dir ('rxdemo-ui') {
                sh 'pwd'
               }
            }   
        }
        
    }
}
    
