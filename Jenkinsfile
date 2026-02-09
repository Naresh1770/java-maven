pipeline{
  agent any
  stages{
    stage('GIT'){
        steps{
            git url: 'https://github.com/Naresh1770/java-maven.git',
                branch: 'main'
        }
    }
  }
  stages{
    stage('MVN'){
        steps{
           sh 'mvn pacakge'
        }
    }
  }
  }
