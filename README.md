<h3>DSCI_511_Project<h/3>
<h1>People's Interests During COVID19 Lockdown: A Review of Search Trends</h1>

<b>Clone the current repository to your local machine using the following line of code:</b>

<pre>
git clone https://github.com/Pawan429/DSCI_511_Project.git
</pre>

<b>Dependencies</b>.  <br>
Install all relevant dependencies using the following code in the Command Prompt.  <br>
<pre>
$ pip install -r requirements.txt
</pre>

<h1>The Dataset</h2>
<b>Problem Statement</b><br>
The creation of our dataset began with a thorough discussion of what type of data can the team build and how relevant it could be to the contemporary reality. After a series of discussions, the team resolved on looking into how the prevailing lockdowns due to COVID-19 are impacting people's everyday preferences and choices. The team then set out to explore literature for relevant information. We found an interesting article by Harris & Haasch (2020) in the Business Insider which the team modeled the dataset's variables after. The data/observations for these variables were then obtained from Google Search & Bing search APIs using the Python. <br><br>
PyTrends module <br>
<pre>pip install PyTrends</pre>
Azure cognitive services module <br>
<pre>pip install azure-cognitiveservices-search-websearch</pre><br>
These module(s) allowed us to retrieve data from Google Search Trends and Bing Search Trends, showing data for search queries that people have made by time periods, regions, topics, etc. To further enrich the dataset related queries were brought in from Google Search API and Bing Search API, to create a more holistic view of related searchtrends across the internet during the quarantine.
