node {
  stage("Test") 
  {
    try{
        echo 'Hello a!'
       
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
  
