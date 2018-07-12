pipeline {
  agent any
  stages {
    stage('check out') {
      parallel {
        stage('1check out') {
          steps {
            echo '1check out'
          }
        }
        stage('parallel1ofcheck out') {
          steps {
            echo 'parallel1ofcheck out'
          }
        }
        stage('parallel2ofcheck out') {
          steps {
            echo 'parallel2ofcheck out'
          }
        }
        stage('parallel3ofcheck out') {
          steps {
            echo 'parallel3ofcheck out'
          }
        }
      }
    }
    stage('build') {
      parallel {
        stage('1build') {
          steps {
            echo '1build'
          }
        }
        stage('Paralle1OfBuild') {
          steps {
            echo 'Paralle1OfBuild'
          }
        }
      }
    }
  }
}
