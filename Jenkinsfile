pipeline{
    agent none
    stages {
        stage("first"){
            steps {
                      logstash{ 
                       echo "hello world 1"
                      }
            }
        }
        stage("second"){
            steps{
                    logstash {
                        echo "hello world 2"
                    }
            }
        }
    }
}