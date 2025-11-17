pipeline {

 agent any

tools {jdk 'JAVA_HOME', maven 'M2_HOME'}

 stages {

 stage('GIT') {

           steps {

               git branch: 'master',

               url: 'https://github.com/Xxazizosxx/Med-Aziz-Logtari-4TWIN8.git'

          }

     }

 stage ('Compile Stage') {

 steps {

 sh 'mvn clean compile'

 }

 }

 }

}

