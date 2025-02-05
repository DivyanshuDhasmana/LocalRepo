<h1>Sentiment Analysis of YouTube Comments</h1>

<p>This project performs sentiment analysis on YouTube comments using the <b>VADER Sentiment Analysis</b> tool and the <b>YouTube Data API</b>. The goal is to extract comments from YouTube videos, filter them based on specific criteria (such as comments with emojis), and analyze their sentiment (positive, negative, or neutral). A bar chart and pie chart are generated to visualize the results of the sentiment analysis.</p>

<h2>Project Features</h2>
<ul>
    <li>Fetches comments from any public YouTube video.</li>
    <li>Filters out irrelevant comments (those with links, no text, or only emojis).</li>
    <li>Performs sentiment analysis on each comment using VADER sentiment analysis.</li>
    <li>Visualizes sentiment distribution with bar and pie charts.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li><b>Python</b> - The programming language used for the project.</li>
    <li><b>VADER Sentiment Analysis</b> - For analyzing the sentiment of the comments.</li>
    <li><b>Google YouTube Data API</b> - For fetching the comments from YouTube.</li>
    <li><b>Matplotlib</b> - For data visualization (Bar Chart, Pie Chart).</li>
    <li><b>emoji</b> - For counting emojis in comments.</li>
</ul>

<h2>Installation</h2>
<p>To run this project, you will need to install the following Python packages:</p>
<pre>
pip install emoji
pip install vaderSentiment
pip install google-api-python-client
pip install matplotlib
</pre>

<h2>Usage</h2>
<ol>
    <li>Clone the repository to your local machine.</li>
    <li>Install the required dependencies (listed above).</li>
    <li>Obtain a <a href="https://console.developers.google.com/">Google API Key</a> for the YouTube Data API v3 and replace the placeholder in the code with your key.</li>
    <li>Run the script and input the YouTube video URL when prompted.</li>
    <li>The script will analyze the comments, filter them, perform sentiment analysis, and output the results with visualizations.</li>
</ol>

<h2>Example Output</h2>
<p>After running the script, the following outputs will be displayed:</p>
<ul>
    <li>The average sentiment polarity (positive, negative, or neutral) of the comments.</li>
    <li>The comment with the most positive sentiment.</li>
    <li>The comment with the most negative sentiment.</li>
    <li>Bar and Pie charts showing the distribution of sentiments (positive, negative, neutral).</li>
</ul>

<h2>Contributing</h2>
<p>If you want to contribute to this project, feel free to fork the repository and submit a pull request. All contributions are welcome!</p>


<h2>Contact</h2>
<p>If you have any questions or suggestions, feel free to open an issue or reach out to me directly:</p>
<ul>
    <li>Email: <a href="divyanshudhasmana9@gmail.com">divyanshudhasmana9@gmail.com</a></li>
    <li>GitHub: <a href="https://github.com/DivyanshuDhasmana">DivyanshuDhasmana</a></li>
</ul>

<h2>Acknowledgments</h2>
<ul>
    <li>Thanks to the <a href="https://developers.google.com/youtube/v3">YouTube Data API</a> for allowing access to video data and comments.</li>
</ul>

