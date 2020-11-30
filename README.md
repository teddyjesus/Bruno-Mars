## Text Analysis of Bruno Mars' Music

As a fan of Bruno Mars, I decided to conduct an exploratory analysis of his music over the years. Using the Genius API, I collected 28 song lyrics from his three studio albums: *Doo-Wops & Hooligans* (2010), *Unorthodox JukeBox* (2012), and *24K Magic* (2016). 

Following text preprocessing, I created word clouds to visualize word frequencies in each album. The word "love" appears significantly more in *XX4K* than the first two albums. As expected, the results of my sentiment analysis showed that most of Bruno Mars' songs are predominantly positive. *Liquor Store Blues* and *Talking to the Moon* have lower percentages of positive words on average. These two songs artificially deflated the overall positivity of *Doo-Wops & Hooligans*. Exact scores from the sentiment analysis can be found in *data_analysis.ipynb.*

Note that my corpus consists of only one artist, so the song lyrics are homogenous in nature. Perhaps I should have compared different artists or collected songs from multiple genres. Having looked at similar projects online, many people indeed analyze larger volumes of songs—and not just from one artist. This project marks my transition from R to Python. 
