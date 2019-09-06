node {
  stage("Test") 
  {
    try{
        echo 'Hello H!'
       
    } 
    catch(Exception e){
                slackSend message: "$e"
                exit
              }
  }
  stage("Slack message")
  {
            slackSend message: "build finished"              
    }
}
  
