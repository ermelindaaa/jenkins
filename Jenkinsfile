node {
  stage("Tes") 
  {
    try{
        echo 'Hello A!'
        docker get image
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
  
