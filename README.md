I'm a fan of Bruno Mars, so I decided to perform an exploratory analysis of his music over the years. Using the Genius API, I collected 28 song lyrics from his three studio albums: *Doo-Wops & Hooligans* (2010), *Unorthodox JukeBox* (2012), and *24K Magic* (2016). 

Following text preprocessing, I created word clouds to visualize word frequencies in each album. The word "love" appears significantly more in *XX4K* than the first two albums. As expected, the results of my sentiment analysis showed that most of Bruno Mars' songs are predominantly positive. *Liquor Store Blues* and *Talking to the Moon* have lower percentages of positive words on average. These two songs artificially deflated the overall positivity of *Doo-Wops & Hooligans*. Exact scores from the sentiment analysis can be found in Data Analysis.ipynb.

Note that my corpus consists of only one artist, so the song lyrics are homogenous in nature; it was a little bit challenging to develop interesting insights. Perhaps I should have compared different artists or collected songs from multiple genres. Having looked at similar projects online, many people indeed analyze larger volumes of songs—and not just from one artist. 

But as someone who recently began the transition from R to Python, this short project certainly improved my knowledge of Python.
