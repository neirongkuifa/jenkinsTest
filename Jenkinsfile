#!/usr/bin/env groovy
properties([ pipelineTriggers([upstream(threshold: 'STABLE', upstreamProjects: 'pipeTest, ')])])
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
