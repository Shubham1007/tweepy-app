# tweepy-app
Use Twitter Search/Streaming API to fetch are store the target tweets with metadata.

<h1>Twitter Stream Filter API(TweetBot)</h1><br/>
APIs has been created to store twitter streaming data and retrieve data based on applied filters. It is a set of 3 APIs-<br/>

API to trigger Twitter Stream<br/>
API to filter/search stored tweets<br/>
API to export filtered data in CSV<br/>
<h1>Technologies used:</h1><br/>

Python<br/>
Flask framework<br/>
ElasticSearch<br/>
Twitter Streaming API<br/>
<h1>To setup project (Installation Instructions)</h1><br/>
clone the project<br/>
cd to project folder cd twitterapibackend and create virtual environment virtualenv venv<br/>
activate virtual environment source venv/bin/activate<br/>
install requirements after activating virtual environment pip install -r requirements.txt<br/>
Change the twitter stream Api credentials in configure.py file.<br/>
