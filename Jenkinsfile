node {
  stage("Tes") 
  {
  echo 'Hello A!'
  }
  stage("Slack message")
            {
              try{
                sh 'docker images'
              }
              catch(Exception e){
                slackSend message: "$e"
              }
              
    }
}
  
