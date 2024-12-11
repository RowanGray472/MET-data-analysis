## MET-data-analysis

This repo contains an analysis of the Metropolitan Museum of Art's Dataset. 
I'm particularly interested in modeling the `isHighlight` variable, and seeing how/if I can predict it.
The dataset: https://github.com/metmuseum/openaccess

My full analysis is in the `MET-data-analysis.Rmd` file, but here's a quote from the introduction to summarize what I'm doing.

This project will analyze data from the Metropolitan Museum of Art in New York that describes their collection. 
This dataset contains a variable called `Is Highlight`, which according to the MET's website, is a boolean variable set to true if an artwork is "a popular and important artwork in the collection". 
I'm really interested to see what variables predict an artwork's status as a popular and important work and seeing what trends I can find. Here's three specific questions on that theme.

Question 1: Which variables have the highest correlation with `isHighlight`?
Question 2: If I'm artist and want the MET to think my art is "a popular and important artwork in the collection" what kind of art should I make?
Question 3: What time periods and cultures are the best-represented among the MET's "popular and important artwork"?

I answer these questions in much more robust detail in the Conclusions section, but here's a topline summary of my results.

1. The variables with the largest and most robust effect on whether an artwork is a highlight have to do with the medium. Specifically, Stone Sculpture and Paintings are the most successful.
2. Culture seems to have no impact on the highlight worthiness of your art most of the time, but there are some edge cases.
3. What year you created your work has no impact on whether your art is a highlight, but what year the MET bought your work is extremely robustly associated with highlight status, but at a very low level.
