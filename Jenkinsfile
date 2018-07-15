#!/usr/bin/groovy

ode("launchpad-nodejs") {
  checkout scm
  stage("Build") {
    sh "npm install"
  }
  stage("Deploy") {
    sh "npm run openshift"
  }
}
