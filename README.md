# Project V.E.R.I.T.A.N.: Visual Exploration & Real-time Insightful Trend Analysis Network

Summary:
This algorithm, powered by Python and machine learning supercharges social media analysis, combining automated data collection, advanced language processing, and interactive visualizations. It enables users to decode Twitter discourse and spot patterns effortlessly.

Explanation:
This algorithm, powered by Python and machine learning, analyzes daily tweets on a dynamic number of input subjects or daily trends. It can be as precise as one keyword such as "malware" to a list of any word that comes to mind. Its aim is to understand the what and why someone or something is being tweeted about at a glance and present the findings visually in an interactive and searchable manner.

Traditionally, twitter can bring good insights into what is going on in the world and what people's reactions are. However, this can take a couple minutes to read through tweets to gather a conclusion per topic. With this code and visualization, you can understand the what and why of these trends in a matter of seconds and for multiple trends.

Starting with user input words, the algorithm begins automated Twitter searches for related tweets. Once all the tweets are gathered, automatic data cleaning follows, removing duplicates, URLs, special characters, and more. Text becomes lowercase, and missing data is handled.

The core process involves a machine learning word2vec model. This converts tweets into numerical vectors that can be used by our visualization to capture word meanings and relationships.

These vectors lead to an interactive visualization, positioning words in a high-dimensional space that reflects their associations. Users can navigate this interactive visualization and even search for a certain keyword allowing them to explore word relationships for instant insights.

The system's simplicity is key. With an initial input and a click of the run button, it automates collection, cleaning, vectorization, and visualization. Users access a streamlined way to dive into tweet interactions without technical expertise.

Visualization:
https://projector.tensorflow.org/?config=https://gist.githubusercontent.com/JaylenTurner/c654aed69f7b233f3fc6eefbddcb5391/raw/901789c0a97beaf411b9c3bfa4aa2827751715e2/projectorConfig.json

Source Code:
https://colab.research.google.com/drive/1JFl1tBUr9pFbQRtNmoxJm-UxIm7jvWcp?usp=sharing
