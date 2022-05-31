# Fin-SoMe: 10,000 Expert-annotated Financial Social Media Data
# Introduction
Fin-SoMe is a dataset with 10,000 labeled financial tweets annotated by experts from both the front desk and the middle desk in a bank's treasury. These annotated results reveal that (1) writer-labeled market sentiment may be a misleading label; (2) writer's sentiment and market sentiment of an investor may be different; (3) most financial tweets provide unfounded analysis results; and (4) almost no investors write down the gain/loss results for their positions.

# Format
The Fin-SoMe dataset is consisted of "tweet", "writer_market_sentiment", "market_sentiment", "sentiment", "reason" and "position" in json format.

# Example
```yaml
{

'tweet': '$WEED.CA Namaste up 40% this morning and just broke $1! Glad I bought in at $.31! All my pot stocks are up! FACK YEAH! ;)',

'market_sentiment': 'Bullish',

'sentiment': 'Positive',

'reason': 'Founded',

'position': 'Unsure',

'writer_market_sentiment': 'bullish'

}
```
# Download
Please write us an email with the agreement. Click [here](http://nlg.csie.ntu.edu.tw/nlpresource/FinSoMe/Fin-SoMe_agreement.pdf) to download the agreement of Fin-SoMe.

Email Address: cjchen@nlg.csie.ntu.edu.tw

# How to Cite the Corpus
Please cite the following paper when referring to the Fin-SoMe in academic publications and papers.

Chung-Chi Chen, Hen-Hsen Huang, and Hsin-Hsi Chen. 2020. Issues and Perspectives from 10,000 Annotated Financial Social Media Data. In Proceedings of the 12th of the Language Resources and Evaluation Conference (LREC 2020), Marseille, France.
# License
Fin-SoMe is licensed under the [Creative Commons Attribution-Non-Commercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.
