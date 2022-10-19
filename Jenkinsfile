node {
    stage('clone') {
        
        git 'https://github.com/Makan763/jenkins-helloword.git'
    
    }
     stage('Build') {
         
         sh label: 'build', script: 'javac Main.java'
    
    }
     stage('Run') {
         sh label: 'run', script: 'java Main'
    
    }
}
