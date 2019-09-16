# awesomation

The only satirical automation tool you will ever need.

## Usage

In what ever pipeline tool you are using replace wasteful steps by calling the silver bullet instead.

In the commandline it looks like this:
`./silver-bullet.sh`

A Jenkinsfile for using the silver bullet could look like so:
```
pipeline {
    agent any
    stages {
        stage('Important stuff!') {
            steps {
                sh './silver-bullet.sh'
            }
        }
    }
}


