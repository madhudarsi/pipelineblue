pipeline {
  agent any
  stages {
    stage('dispaly') {
      agent any
      steps {
        echo 'hello world'
        sh '''#!/bin/bash
for i in {1..4}
do
echo $i
done'''
      }
    }

    stage('maven build') {
      agent any
      steps {
        sleep 60
      }
    }

  }
}