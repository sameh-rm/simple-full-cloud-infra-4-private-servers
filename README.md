# UdacityProject2

udacity cloud devops engeneer project 2

## What is it ?

The goal of the project is to provide some cloudformation scripts to deploy web servers for a highly available web app.

## how is the project cut out ?

there are two parts in this project

- network scripts
- servers scripts

## what are the requirements to run it ?

Amazon aws account and a bucket already deployed having the web app code . Don't forget to adapt the userData to match your webapp sources location

## how to run it ?

you can run the part as followed :

./create.sh [stackName1] infra.yml infra-params.json
./create.sh [stackName2] servers.yml servers-paramrs.json
