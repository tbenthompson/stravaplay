# stravaplay

Caveat: Sloppy and just "done" enough for the results I wanted. 

Instructions:

1) Set up your Strava API keys. "Create and Manage your App" here: https://developers.strava.com/ (for website, you can put anything and for "authorization callback domain", just put "localhost")
2) Clone this repo.
3) Create a file in the repo directory called "client.secret" with the only contents being your "Client ID" and "Client Secret" separated by a comma.
4) Run "download.py" to grab all your activities
5) Run "process.py" to make a nice figure of MEQ, distance and elevation

This uses the https://github.com/hozn/stravalib library which needs to installed with "pip install stravalib". Also, pandas and other common libraries!
