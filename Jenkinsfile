pipeline {
agent any

stages {  

    stage('Clone Repository') {  
        steps {  
            git url: 'https://github.com/username/jenkins-simple-demo.git', branch: 'main'  
        }  
    }  

    stage('Run Script') {  
        steps {  
            sh 'chmod +x script.sh'  
            sh './script.sh'  
        }  
    }  

}  

}
