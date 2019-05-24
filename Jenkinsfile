#!/usr/bin/env groovy
properties([ pipelineTriggers([upstream(threshold: 'FAILURE', upstreamProjects: 'Pipe, ')])])
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
