# java-slack-custommessage-project
 This is for pushing custom messages into slack channels using slack apis.
 This is a simple java maven based project.The slack dependencies have been added in the pom.xml.
 
 The steps that one need to follow to obtain the web hook url:

1. Create an app in slack.This can be done here-https://api.slack.com/apps?new_app=1
2. Activate incoming webhooks for a particular channel.This can be done by navigating to https://api.slack.com and choosing Incoming WebHooks from the side  
   navigation bar.Note the webhook url
4. From OAuth & Permissions note the auth token and add  ,read and write scope to the token.

The WebHook URL obtained in step 2 should be used in the code.
