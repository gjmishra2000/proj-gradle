node {
  stage('Clone sources') {
    git url: 'https://github.com/gjmishra2000/proj-gradle.git'
  }
  stage('test') {
     sh 'cd complete && ./gradle test'
     }
 
  stage('run') {
     sh 'cd complete && ./gradle run'
     }
}
