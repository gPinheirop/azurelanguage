# Simple Azure language Service Test

![image](https://github.com/user-attachments/assets/aeb84252-a9f7-4920-aa5e-8883787b35ff)

## Language Analysis
This repo uses azure language service to get some valueable data from text imputs

## How to run it
```bash
node src/index.js
```

## Results

```
=== Sentiment analysis and opinion mining sample ===
- Document 0
        Document text: The food and service were unacceptable. The concierge was nice, however.
        Overall Sentiment: negative
        Sentiment confidence scores: { positive: 0, neutral: 0, negative: 1 }
        Sentences
        - Sentence sentiment: negative
          Confidence scores: { positive: 0, neutral: 0, negative: 1 }
          Mined opinions
                - Target text: food
                  Target sentiment: negative
                  Target confidence scores: { positive: 0.01, negative: 0.99 }
                  Target assessments
                        - Text: unacceptable
                          Sentiment: negative
                - Target text: service
                  Target sentiment: negative
                  Target confidence scores: { positive: 0.01, negative: 0.99 }
                  Target assessments
                        - Text: unacceptable
                          Sentiment: negative
        - Sentence sentiment: neutral
          Confidence scores: { positive: 0.22, neutral: 0.75, negative: 0.04 }
          Mined opinions
                - Target text: concierge
                  Target sentiment: positive
                  Target confidence scores: { positive: 1, negative: 0 }
                  Target assessments
                        - Text: nice
                          Sentiment: positive
- Document 1
        Document text: The food and service were amazing! The concierge was bad, however.
        Overall Sentiment: mixed
        Sentiment confidence scores: { positive: 0.5, neutral: 0.02, negative: 0.48 }
        Sentences
        - Sentence sentiment: positive
          Confidence scores: { positive: 1, neutral: 0, negative: 0 }
          Mined opinions
                - Target text: food
                  Target sentiment: positive
                  Target confidence scores: { positive: 1, negative: 0 }
                  Target assessments
                        - Text: amazing
                          Sentiment: positive
                - Target text: service
                  Target sentiment: positive
                  Target confidence scores: { positive: 1, negative: 0 }
                  Target assessments
                        - Text: amazing
                          Sentiment: positive
        - Sentence sentiment: negative
          Confidence scores: { positive: 0, neutral: 0.04, negative: 0.96 }
          Mined opinions
                - Target text: concierge
                  Target sentiment: negative
                  Target confidence scores: { positive: 0, negative: 1 }
                  Target assessments
                        - Text: bad
                          Sentiment: negative
- Document 2
        Document text: The food was good but the music was so loud. The concierge was nice.
        Overall Sentiment: mixed
        Sentiment confidence scores: { positive: 0.47, neutral: 0.09, negative: 0.45 }
        Sentences
        - Sentence sentiment: negative
          Confidence scores: { positive: 0.05, neutral: 0.06, negative: 0.89 }
          Mined opinions
                - Target text: food
                  Target sentiment: positive
                  Target confidence scores: { positive: 1, negative: 0 }
                  Target assessments
                        - Text: good
                          Sentiment: positive
                - Target text: music
                  Target sentiment: negative
                  Target confidence scores: { positive: 0.08, negative: 0.92 }
                  Target assessments
                        - Text: loud
                          Sentiment: negative
        - Sentence sentiment: positive
          Confidence scores: { positive: 0.88, neutral: 0.11, negative: 0 }
          Mined opinions
                - Target text: concierge
                  Target sentiment: positive
                  Target confidence scores: { positive: 1, negative: 0 }
                  Target assessments
                        - Text: nice
                          Sentiment: positive
- Document 3
        Document text: The food and service were amazing! And The concierge was nice.
        Overall Sentiment: positive
        Sentiment confidence scores: { positive: 0.93, neutral: 0.06, negative: 0 }
        Sentences
        - Sentence sentiment: positive
          Confidence scores: { positive: 1, neutral: 0, negative: 0 }
          Mined opinions
                - Target text: food
                  Target sentiment: positive
                  Target confidence scores: { positive: 1, negative: 0 }
                  Target assessments
                        - Text: amazing
                          Sentiment: positive
                - Target text: service
                  Target sentiment: positive
                  Target confidence scores: { positive: 1, negative: 0 }
                  Target assessments
                        - Text: amazing
                          Sentiment: positive
        - Sentence sentiment: positive
          Confidence scores: { positive: 0.87, neutral: 0.12, negative: 0.01 }
          Mined opinions
                - Target text: concierge
                  Target sentiment: positive
                  Target confidence scores: { positive: 1, negative: 0 }
                  Target assessments
                        - Text: nice
                          Sentiment: positive
- Document 4
        Document text: The food and service were unacceptable. The concierge was rude.
        Overall Sentiment: negative
        Sentiment confidence scores: { positive: 0, neutral: 0, negative: 1 }
        Sentences
        - Sentence sentiment: negative
          Confidence scores: { positive: 0, neutral: 0, negative: 1 }
          Mined opinions
                - Target text: food
                  Target sentiment: negative
                  Target confidence scores: { positive: 0.01, negative: 0.99 }
                  Target assessments
                        - Text: unacceptable
                          Sentiment: negative
                - Target text: service
                  Target sentiment: negative
                  Target confidence scores: { positive: 0.01, negative: 0.99 }
                  Target assessments
                        - Text: unacceptable
                          Sentiment: negative
        - Sentence sentiment: negative
          Confidence scores: { positive: 0, neutral: 0, negative: 1 }
          Mined opinions
                - Target text: concierge
                  Target sentiment: negative
                  Target confidence scores: { positive: 0, negative: 1 }
                  Target assessments
                        - Text: rude
                          Sentiment: negative
```
