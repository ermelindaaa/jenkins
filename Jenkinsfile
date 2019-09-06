node {
  stage("Tes") 
  {
    try{
        echo Hello A!'
    } 
    catch(Exception e){
                slackSend message: "$e"
                return
              }
  }
  stage("Slack message")
  {
            slackSend message: "build finished"              
    }
}
  
