# YouTube Data Analysis and Visualization
This project utilizes the YouTube API to fetch and analyze data from various YouTube channels. It visualizes key metrics such as subscriber count, view count, and total number of videos for a given set of channels.

### Installation
First, clone the repository to your local machine:

git clone https://github.com/yourusername/youtube-data-analysis.git

### Install the required packages using pip:

pip install google-api-python-client pandas seaborn matplotlib

# API Key Setup
To use the YouTube API, you need to have an API key. Follow these steps to get your API key:

- Go to the Google Cloud Console.
- Create a new project or select an existing project.
- Navigate to the API & Services > Credentials.
- Click on Create Credentials and select API Key.
- Copy the generated API key.
- Replace the api_key variable in the script with your API key.

# Usage
The script fetches data for a list of YouTube channels and visualizes it. Here are the main steps involved:

- Define a list of YouTube channel IDs.
- Use the get_channel_stats function to fetch channel statistics.
- Convert the fetched data into a Pandas DataFrame.
- Perform data cleaning and transformations.
- Visualize the data using Seaborn and Matplotlib.

# Visualizations
The script generates the following visualizations:

- Number of Subscribers for Each Channel
- Number of Views for Each Channel


- Number of Videos for Each Channel
