#!/usr/bin/env groovy
properties([[$class: 'JiraProjectProperty'], pipelineTriggers([upstream(threshold: 'STABLE', upstreamProjects: 'Pipe, ')])])
pipeline{
    agent any

    stages{
        stage("Test"){
            steps{
                echo "Test in master"
            }
        }
    }
}
