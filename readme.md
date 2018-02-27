# Test app for Pluralsight course

This is a quick and dirty test node.js app cobbled together for the purposes of demonstrating a basic CI/CD workflow with Docker Hub for a Pluralsight video training course..

## Instructions for use

All of the files included in the .zip file (available to Plus subscribers) should be unzipped into a new directory.

Initializing a Git repo and making a remote of it on GitHub are explained in Module 2 of the course.

The viewer should have Git installed and have a GitHub account.

Notes:

The following must be used as a value for DOCKER_HUB_TRIGGER environment variable in the Cirle CI tool

curl -H "Content-Type:application/json" --data {"build":true} -X POST https://registry.hub.docker.com/u/sanjaymodha/docker-ci/trigger/1c7d9860-f78b-4c9c-b673-1555adc0f8fd/
