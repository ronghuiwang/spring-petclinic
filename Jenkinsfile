#!groovy
pipeline {
	agent none
        tools {
    maven 'M3'
  }
  stages ('Build') {
      steps {
      	sh 'mvn clean install'
      }
  }
}
