#!groovy
// Run docker build
pipeline { agent { label 'master'
        }
    stages { stage("create docker image") { 
        steps { echo "-------------------- start building image --------------" 
           sh 'docker build . -t my_html_v.1'
            }
        }
    }
}
