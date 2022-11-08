# Mission-to-Mars
## Purpose of Analysis
For the first part of the analysis, automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). The titles and preview text of the news articles were scraped and extracted, and the scraped info was stored in a Python data structure. 
For the second part of the analysis, automated browsing was used to visit the Mars temperature data site, and the HTML code was extracted. The Mars data table was scraped and extrated, and stored in a Pandas DataFrame. 
The following observations were made with the scraped data:
- There are 12 months on Mars
- The dataset contains 1,867 Martian days worth of data
- Months 3 and 4 are the coldest months with an average temperature of -83 C
- Month 8 is the warmest month with an average temperature of -68 C
- Month 6 has the lowest atmospheric pressure with an average of 745 Pascals
- Month 9 has the highest atmospheric pressure with an average of 913 Pascals
- One Martian year is equivalent to 686 days on Earth.
