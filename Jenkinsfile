node {
  stage("Tes") 
  {
    try{
        echo 'Hello A!'
    }
  }
  stage("Slack message")
            {
              catch(Exception e){
                slackSend message: "$e"
              }
              
    }
}
  
