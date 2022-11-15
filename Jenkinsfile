#!groovy
@Library('Librerias') _

pipeline {
  agent any
  stages{
    stage("Prepare environment") {
      steps {
        echo '-=- prepare build environment -=-'
      }
    }
    stage("Compile") {
      steps {
        echo '-=- Compile code -=-'
      }
    }
    stage("Unit tests") {
      steps {
        echo '-=- execute unit tests -=-'
      }
    }
    stage("Mutation tests") {
      steps {
        echo '-=- execute mutation tests -=-'
      }
    }
    stage("Dependency vulnerability") {
      steps {
        echo '-=- dependency vulnerability scans -=-'
      }
    }
    stage("code inspection") {
      steps {
        echo '-=- code inspection -=-'
      }
    }
    stage("Package") {
      steps {
        echo '-=- package application -=-'
      }
    }
    stage("Build & push container image") {
      steps {
        echo '-=- build and push container image -=-'
      }
    }
    stage("Run ephimeral test environment") {
      steps {
        echo '-=- run ephimera test environment -=-'
      }
    }
    stage("Integration tests") {
      steps {
        echo '-=- execute integration tests -=-'
      }
    }
    stage("Performance tests") {
      steps {
        echo '-=- execute performance tests -=-'
      }
    }
    stage("Promote container image") {
      steps {
        echo '-=- promote container image -=-'
      }
    }
    post{
      always{
        echo '-=- cleaning up resources -=-'
      }
    }
  }
}