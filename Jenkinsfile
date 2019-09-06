node {
  stage("Test") 
  {
  echo 'Hello A!'
  }
  stage("Slack message")
            {
                slackSend message:"build finished "
            }
}
  
