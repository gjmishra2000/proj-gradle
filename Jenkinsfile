node {
  stage('Clone sources') {
    git url: 'https://github.com/gjmishra2000/proj-gradle.git'
  }
  stage('test') {
     sh 'cd complete && ./opt/gradle/gradle-6.7/bin/gradlew test'
     }
 
  stage('run') {
     sh 'cd complete && ./opt/gradle/gradle-6.7/bin/gradlew run'
     }
}
