node('UBUNTU'){
    stage('GIT'){
    git 'https://github.com/hanocc/openmrshanock.git'
    }
     stage('package'){
      sh 'mvn package'
     }  

}