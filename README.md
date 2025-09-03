# Text-Classification-of-News-Articles-with-Speed-Volume-and-Circuitousness


This is a my version of the code implementation of the research, Toubia, O., Berger, J.A., & Eliashberg, J. (2021). How quantifying the shape of stories predicts their success. Proceedings of the National Academy of Sciences of the United States of America, 118.

The paper attempts to calculate the speed, volume and circuitousness of text. The definitions of speed, volume and circuitousness are as follows:

They propose quantifying the text by calculating their speed, volume and circuitousness

**Speed**- sum of distance between consecutive points or chunks of text divided by length of text

**Volume**- Volume of the the minimum volume ellipsoid that covers all points

**Circuitousness**- ratio of actual distance travelled between text points to the shortest path

These quantification metrics are calculated on text from an open-source news dataset; This is an open source dataset composed of millions of news articles mostly scraped from a curated list of 1001 domains from http://www.opensources.co/. Because the list does not contain many reliable websites, additionally NYTimes and WebHose English News Articles articles has been included to better balance the classes.

