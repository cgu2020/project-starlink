# project-starlink
This is a repository for "Measuring Starlink Latency from RIPE Atlas"
You can use this repository to measure starlink’s latency.
After you follow the steps below, you should have a graph that will display the different latencies from each RIPE Atlas Starlink probe over a 24-hour period.
Step 0: Installing the requirements
Download the repository. You should make sure you have installed python >=3.0 and jupyternotebook. Install the requirements with pip install -r requirements.txt 
Step 1: Make an API key and obtain credits with RIPE Atlas
Make an account with Ripe Atlas and create an API Key. Purchase credits so that you can run the measurements. We calculated we needed around 11,000 credits to run the measurements every 15 minutes for a full day. 
Step 2: Replace the API KEY
In part three, replace our Api Key with the new key given by the account you just created
Step 3: Run the code

Start the notebook server from the command line:
jupyter notebook
Open starlink.inpyb and execute the various parts.
