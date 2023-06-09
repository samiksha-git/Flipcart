pipeline {
         agent any

         stages {
               stage('Checkout') {
                     steps {
                             checkout scm
                             }}
                   satge ('Build') {
                     steps {
                          sh '/home/samiksha/Documents/Devops-tools/apache-maven-3.9.1/bin/mvn install'
                          
                          }}
                       stage('Deployment') {
                          steps {
                                 sh 'cp /home/samiksha/Documents/Devops-tools/apache-tomcat-9.0.73/webapps'
                     }

}}}

