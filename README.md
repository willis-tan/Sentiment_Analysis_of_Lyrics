# Usage

Scrape lyrics from your favorite artists and find out what their most commonly used words are. You will also learn the lexical richness (# of unique tokens / # of tokens) and the amount of positive, neutral, or negative lyrics per artist.

# Required packages

Use `pip` to install the following packages:  

```bash
pip install lyricsgenius
pip install pandas
pip install matplotlib
pip install wordcloud
pip install nltk
```
To avoid missing packages in nltk, just run `python -m nltk.downloader all` in the terminal.

# How to run the notebook
If you want to analyze lyrics from different artists:
1. Sign up for a Genius API token [here](https://genius.com/api-clients). Make sure to read over necessary guidelines.  
2. Copy paste your token into the first cell of the note book. Include any terms you want to filter out, such as live or demo versions.
3. Edit the artists list in the 2nd cell and specify how many songs per artist. Then run the 2nd cell.  
 **Caution,** running the cell again will redownload all lyrics.
4. Run the rest of the cells. Sit and back and wait for the results.
