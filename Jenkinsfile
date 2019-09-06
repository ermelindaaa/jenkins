node {
  stage("Test") 
  {
  echo 'Hello B!'
  }
  stage("Slack message")
            {
                slackSend message:"build finished "
            }
}
  
