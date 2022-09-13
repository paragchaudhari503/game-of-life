 pipeline {
   agent {
     node {
              label 'Built-In Node'
     }
   }
   stages {
     stage ('clone') {
       steps {
         sh "cd /mnt"
         sh "mkdir projects"
         sh "cd /mnt/projects"
       sh "git clone https://github.com/paragchaudhari503/game-of-life/"
         
         
         
       }
     }
   }
}
