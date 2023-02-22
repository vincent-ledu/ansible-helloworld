# Ansible Kata

Source: this exercice is based on https://acklenavenue.com/competencies/ops/kata/kata-level1.html

## Step 1

Clone this project in a local directory

## Step 2

Launch the hello world playbook

## Step 3

Write a role to install this project on target: https://github.com/abkunal/Chat-App-using-Socket.io

### Step 3.1

Create an ansible role to:

- install nodejs
- install pm2
- clone app https://github.com/abkunal/Chat-App-using-Socket.io in /opt/chat_app
- launch the application with command:
  - pm2 start app.js

### Step 4

- create a docker image with the previous app
- launch the application in docker

## Step 5

- use the local minikube instance to launch de app in minikube
