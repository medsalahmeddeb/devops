pipeline{
    agent any
     stage("Maven Build"){
       steps{
                sh "mvn clean package"
                sh "mv target/*.war target/myweb.war"
            }
      }
