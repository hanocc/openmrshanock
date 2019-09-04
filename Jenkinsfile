node('UBUNTU'){
    stage('GIT'){
    git 'https://github.com/hanocc/openmrshanock.git'
    }
     stage('package'){
      sh 'mvn package'
     }  
     stage('archiveartifacts'){
         archive 'appsfortesting/target/*.war'
     }

}