pipeline {
   agent any
   stages {
      stage("build") {
          steps {
              sh 'ls -ltr'
              sh 'df -h'
              echo 'build completed succesfully'
              echo 'built succesfully'
          }
      }

      stage("test") {
          steps {
             
              echo 'tested completed succesfully'
              echo 'testedddd'
          }
      }

      stage("deploy") {
          steps {
              echo 'deploy completed succesfully'
              echo 'It worked'
          }
      }

      }


}
