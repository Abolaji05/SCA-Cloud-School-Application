
- [@abolaji05](https://www.github.com/abolaji05)


## Installation

Install my-project 


  pipeline {

    agent any
    stages {
        stage('Building code') {
      steps {
        sh 'python3 sca.py'
          }
        }
    
    stage('Success message') {
      steps {
        sh 'echo "Yes it works"'
      }
    }

    }
}

    
## Documentation

[The code was built on GitHub as a python script to print the message “I, Abolaji Adeyi will be joining the Cloud Engineering She Codes Africa Cohort-3 class in 2022!” and then integrated to Jenkins.
 
The pipeline is what embodies the whole script. The agent (any) was used to communicate to Jenkins on what server to build the code, but because there’s only one Jenkins server, so by default code built on Jenkins server.
The script is a programmatic script (declarative pipeline) because every steps were declared in stages.
The first stage was to build the code required to run the python app (git). Followed by the sh command to run the code.
The next stage was to build success message. For it to get to the second stage, it means it has successfully built the first stage.
echo is the command to print the message and curly braces was used to end step, stage and power pipeline.]
# SCA-Cloud-School-Application
