# TwitterBasicCrawler
A basic Twitter crawler using Python

Twitter application

Open a web browser and go to https://apps.twitter.com/app/new
Sign in with your Twitter username and password if you are not already signed in.
Enter a name, description, and temporary website (e.g. http://ichliebedich.com)
Click "Create your Twitter application"
Click on the "API Keys" tab and then click "Create my access token"
Wait a minute or two and press your browser's refresh button.
You should now see new fields labeled "Access token" and "Access token secret" at the bottom of the page.
You now have a Twitter application that can act on behalf of your Twitter user to read data from Twitter.
Connect your Twitter application to these scripts

Download the code in the repository if you haven't already
Open Athentication.py file in a editor
Update the following lines with the information displayed in the web browser for your application:
    consumer_key="..." #Note this is now called API key 
    consumer_secret="..." #Note this is now called API secret
    access_token="..." 
    access_token_secret="...."
    #Replace the … with whatever values are shown in your web browser. Be sure to keep the quotation marks.
Save the file as myauth.py (not the same name as before)
You are now ready to run a simple example.

First run (streaming_simple.py)

