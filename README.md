# Drake Lyrics
## Description
A project analyzing the frequency of certain words across Drake albums. Some tidytext and NLP practice.\
Drake's discography is one of the most successful in modern music history. This project applies statistical analysis and text mining in R to address key questions:\
-What are the most frequent non-filler words across Drake's lyrics?

-How does the usage of core thematic terms (e.g., love, drake, respect, money, trust) evolve across different albums?

-Is there a relationship between the frequency of romantic terminology (e.g., love) and song engagement/track views?

## Quick Takeaways
Dropping filler words, we can see that Drake leans heavily into, to put it nicely, themes of identity, fame, and relationships across his music, while heavily relying on profanity to get his point across. Also, we can observe that his songs with 50M+ views almost never over-repeat the word "love". His biggest hits are the ones that keep the romance to a minimum, which is quite interesting, because at first glance one would think mentioning the word "love" sells the most tracks. 

## Packages used:

```{r}
library(tidyverse)
library(stringr)
library(tidytext)
library(kableExtra)
library(tm)
library(wordcloud)
library(SnowballC)
```
## Sources:
Drake Lyrics Dataset. (n.d.). Kaggle. https://www.kaggle.com/datasets/juicobowley/drake-lyrics?resource=download
