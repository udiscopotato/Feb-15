pipeline {
  agent any
  
  stages {
    stage("SCM") {
      steps {
        git "https://github.com/udiscopotato/Feb-15.git"
        sh "java Demo.java"
        sh "python3 demo.py"
      }
    }
  }
}
