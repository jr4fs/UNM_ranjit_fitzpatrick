# Save the Children (United Neighbors Mission) 
### Hacking for Human Rights 10/10/2020 - 10/24/2020, UVA School of Data Science 

## Problem Description
The goal of this hackathon is to explore and prototype different options for generating infrastructure damage values that can be applied to MDI’s predictive analytics model.

## Our Contributions
  - Explored extracting information from tweets scraped from Twitter
  - Using a tweet scraper, we collected tweets matching a variety of keywords relating to conflicts and displacement
  - We used a Named Entity Recognition tagger to extract tags from each tweet that captured the most important words from each tweet
  - We explored two main primary sources taken from the IDMC and UNHCR datasets; performed data visualization and feature extraction
### System Design
![High Level Overview](https://github.com/jr4fs/savethechildren/blob/main/idea%202-1.png?raw=true)
## Case Study 1: Afghanistan 
1. Collected tweets using the following queries:
      - Afghanistan, conflict
      - Afghanistan, refugee
      - Afghanistan, displacement
      - Afghanistan, crisis
      - Afghanistan, war
      - Afghanistan, conflict, children
      - Afghanistan, refugee, children
      - Afghanistan, displacement, children
      - Afghanistan, crisis, children
      - Afghanistan, war, children
2. Example Tweet Output: 
3. Queried for "Afghanistan" from primary sources
4. Parsed data into standardized format

## Future Work
- Utilize more sophisticated text models to process tweets
- One way to enhance the information extracted from tweets would be to analyze images along with text from tweets
- This could make use of a captioning model to describe the image or using the image for geolocation using a model such as Google’s PlaNet
- Create map showing the prevalence of given topics in specific regions to help characterize how different areas have been affected
- Use map and location details to provide estimates of where people who have been displaced might travel
- Work to ensure data privacy, making sure the data extracted does not compromise the safety of those who have been displaced

## How to Use this Repo



## Detailed Overview of Research and Work

https://drive.google.com/drive/folders/1NOInwowDxQ53maoIytwMtRervMZt-yKQ?usp=sharing 


