#!/usr/bin/groovy
@Library('github.com/chmouel/osio-pipeline-helpers@master')

pipeline {
    agent any

    parameters {
        booleanParam(defaultValue: true, description: '', name: 'userFlag')
    }

    stages {
        stage("foo") {
            steps {
                echo "flag: ${params.userFlag}"
            }
        }
    }
}
