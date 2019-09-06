node {
  stage("Tes") 
  {
  echo 'Hello B!'
  }
  stage("Slack message")
            {
              try{
                sh 'docker images'
              }
              catch(Exception e){
                slackSend message: e
              }
              
    }
}
  
