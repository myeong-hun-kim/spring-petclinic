pipeline {
  agent any
  // JAVA와 Maven Tool 등록
  tools {
    jdk 'jdk17'
    maven 'M3'
  }

  stages {
    // Github에서 Jenkins로 소스코드 복제
    stage('Git Clone') {
      steps {
        git url: 'https://github.com/myeong-hun-kim/spring-petclinic.git', branch: 'main'
      }
    }
    stage('Maven Build') {
      
    }
    stage('Docker Image') {
      
    }
    stage('Docker Image Push') {
      
    }
    stage('SSH Publish') {
      
    }
  }
}
