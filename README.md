# webex-recording-restfulapi-example

Make sure to have Python 3 installed.

To run the server application, open a command terminal, and navigate to the folder where you saved this Python script. 

Replace the required variables (Client ID, Secrect ID,OAUTH_URL etc...) in the .env,
If you want direct download recording at the backend by python code , you can set IS_DOWNLOAD_BY_CODE is true and update the LOCAL_DOWNLOAD_PATH to 
your local path
then run:

*python3 oauth.py*

You should see this in the terminal:

Listening on http://127.0.0.1:10060...

copy and paste above URL into browser and follow prompts

**Note**: Your Redirect_URI in the Integration's settings on Developer Webex Teams site should be: http://127.0.0.1:10060/oauth or if you're using any other hosting platform it would be https://YOUR_SERVER/oauth
