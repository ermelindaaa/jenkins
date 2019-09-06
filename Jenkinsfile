node {
  stage("Test") 
  {
    try{
        echo 'Hello B!'
       
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
  
