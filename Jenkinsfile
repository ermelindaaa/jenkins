node {
  stage("Test") 
  {
  echo 'Hello !'
  }
  stage("Slack message")
            {
                slackSend message:"build finished "
            }
}
  
