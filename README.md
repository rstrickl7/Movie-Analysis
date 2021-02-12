![austin animal center](./images/austin-animal-center.jpg)

# Microsoft Wants to be in the Movie Biz

**Author**: [Becky Strickland]


## Business Problem

Microsoft has decided to create a new movie studio. Microsoft wants to know what types of films are currently doing the best at the box office to help decide what type of films to create.

## Data

Movie info including titles, ratings, genres from imdb's website.
Movie financial info including budget, domestic  gross, and worldwide gross.


## Methods

This project uses descriptive analysis, including description of trends by genre. This provides an overview of what genres perform the best at the box office and what if any characteristics can help us predict this.

## Results

What type of films are our competitors producing?
![Graph-1](Images/Graph-1.png)



- Genres with most titles:
    1. Drama
    2. Documentary
    3. Comedy
    
    
- We can see from our visualization that our competitors primarily produce films associated with the Drama genre. About 24% of all films examined can be associated with the Drama genre. In second and third place are Documentary and Comedy at around 13-14% each. These three genres dominate all other genres; altogether they account for about half of all films produced.


020, likely as a result of COVID-19.



## Conclusions


- Profits and commonly produced genres:
    No relationship

- Profits and highly rated genres:
    No relationship
    
 - Genres with most profit:
    1. Animation
    2. Adventure
    3. Sci-Fi

## Recommendations

This analysis leads to three recommendations for Microsoft:

- Don't produce genres commonly produced by competitors. These genres do not correlate to profit.
- Don't produce genres solely based on viewer ratings. These genres do not correlate to profit.
- According to our current findings, Microsoft should invest in producing animation films since they have the best success globally.


### Next Steps

Further analyses could  help confirm  our recommendations and yield additional insights:

- Find other profit data source to expand to more titles
- Calculate Profit by Runtime
- Calculate Average # of reviews by genre
- Explore data outside of imdb
- Calculate correlation coefficient
- Investigate 74% of records lost in budget to imbd merge
    - Are the sample records representative of all the data?

## For More Information

See the full analysis in the [Jupyter Notebook](./Movie-Analysis.ipynb) or review this [presentation](./Movie-Analysis-Presentation.pdf).



## Repository Structure

```
├── data
├── images
├── Movie-Analysis.ipynb
├── Movie-Analysis-Presentation.pdf
└── README.md
```