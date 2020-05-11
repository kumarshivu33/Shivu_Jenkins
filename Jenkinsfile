pipeline {
  agent any
  stages {
    stage('FIRST STEP') {
      parallel {
        stage('FIRST STEP') {
          steps {
            echo 'SK_first pipeline '
          }
        }

        stage('Second') {
          steps {
            sh '''#!/bin/bash
echo "shivu kumar first pipeline"'''
          }
        }

        stage('Adding docker') {
          steps {
            echo 'added doker image'
            fileExists 'Sk_firstjob'
          }
        }

      }
    }

  }
}