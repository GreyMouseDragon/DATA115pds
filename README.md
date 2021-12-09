# DATA115pds

**Motivation:**

  The primary motivation for this project was to organize and tidy up the data that I was creating via a Discord bot, which I am still currently building. This bot currently has the functionality to create a card based off of a preset that I have implemented in a SQLite database, and output it to the user, while simultaneously moving the preset data to a different database that holds all generated cards. Not only did I want to make sure that all of the data were being processed correctly, I was also interested in the RNG functions that the bot utilizes in order to makes its decisions.

**Data Process:**

  As mentioned above, the data are processed by the bot in a pre-determined manner, however, in order to obtain the data that the bot needed, I manually translated and entered the cards into the database. In order to make sure what I had entered was correct, I double-checked by randomly looking up values in the data set versus the cards I had obtained them from.

**Visualization:**

![finalprojectvisualization](https://user-images.githubusercontent.com/30054499/145482625-1769ef67-a5a7-491a-9d38-48a6cfd431f8.png)

**Analysis:**

  The five numbers of this data set's number of cards generated are:
    
    Median - 4
    First Quartile - 2
    Third Quartile - 6
    Minimum - 0
    Maximum - 10
    
   This does not discriminate against card rarity, as it groups all generation numbers together for a total of 300 cards analyzed. Interestingly, the maximum value occurs exactly once, whereas the minimum value occurs four times. Additionally, the median is equal to the average of the data.
