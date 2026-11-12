# Notes For Project

## Ideas

- American news outlets and how events have swayed political opinion (quantified by voting (tentative))

## Notes

- Sentiment Analysis
- Tagging
- Temporal Element (Time-Series)
- Binary Target Possibly (Republican and Democrat)
- Talk to polisci dept?
- Polls

## Meeting

Note: Nothing is final, we can change multiple things about our analysis/predictions

### How To Access Data

- Where can we aggregate our sources? Where can we find an archive?
  - Paywalls?
- National level?
- Get election information (easy)

### Sentiment Analysis

- How can we find the relationship between this and election results
- Usually a two dimensional numeric analysis of how “positive” or “negative” something is
- When text mining, we need to make sure where the sentiment lies (x candidate is great, y candidate is great, both positive but pointed towards different parties)
  - NLP (Natural Language Processing)
  - Name-entity recognition
- What issues are people looking at?
  - 2020: “Woke”, the pandemic
  - 2026: Iran war, price of goods

### News

- Articles can be grouped to where they lean:
  - Income Inequality, Palestinian rights → lean left
  - Arguments against trans people, pro corporate → lean right
  - Currently, articles of the Iran war or price of goods are more center, but work against Trump
- News has gone more partisan over time
- Require a variety of sources
- Features for News
  - Text (headlines)
  - Date
  - Location
  - Source

### Datasets

- Recommended 25,000 data points
- Sentiment analysis on all the articles should be okay computationally
- Not bag of words (what Justin said)
- How to structure the columns for sentiment

### Events and Time

- Unique events, things are always changing (pandemic, 9/11)
- New tech, world changes
- Party platforms hasn’t changed much, but the voting blocks have been shifting
  - White voters in small towns have moved more conservative over time

### Scope

- National scope or focus on a certain state?
- Full midterm and presidential, or should we narrow it
  - e.g. we could only look at senators, or solely presidential
  - Have to look at who previously held the seat to see if the seat went to a different direction or stayed
- If narrowed down geographically, we shouldn’t pick a state that almost always leans blue or red
