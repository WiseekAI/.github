# Wiseek

Wiseek scores every SEC filing for market importance (1 to 10) and sentiment in
real time, across about 6,800 US tickers. The product lives at
[wiseek.ai](https://wiseek.ai).

## Open data

We publish free, citable datasets measuring how SEC filings move stocks:

- [wiseek-datasets](https://github.com/WiseekAI/wiseek-datasets): the Filing Impact
  Monthly series. Importance score and sentiment vs next-session excess price
  moves, plus a per-event archive. CC BY 4.0.
- [Live Filing Impact Tracker](https://wiseek.ai/research/filing-impact-index/):
  rolling 90-day event-level data, updated continuously.
- [All datasets and methodology](https://wiseek.ai/datasets/)

From the launch window (Jul 24 to Aug 14, 2026; 11,416 measured filings): filings
Wiseek scored 9 or 10 moved a median 4.99% (excess of the market) by the next
close. Filings scored 1 to 4 moved 2.14%. The gap held in every market-cap band.

## What the Wiseek score is

Every filing that hits SEC EDGAR runs through Wiseek's scoring models within
seconds of publication. The importance score (1 to 10) is calibrated on filing
type, transaction size, insider participation, and how similar disclosures have
historically moved prices. Scores of 7 and up cross Wiseek's publication
threshold and appear on the site. The sentiment label (positive, negative,
neutral) comes from a classifier tuned on corporate-disclosure language, built
to tell a beat-and-raise 8-K from a going-concern 8-K even when both are
written in the same flat legalese.

Scores are assigned when the filing is processed and never revised after the
market reacts. That is what makes this dataset a fair test of the models: the
score always came first, the price move second. Full pipeline:
https://wiseek.ai/methodology/

## More from Wiseek

- Product homepage: https://wiseek.ai/
- Plans and pricing: https://wiseek.ai/pricing/
- Dilution Risk Tracker (free tool): https://wiseek.ai/dilution-tracker/
- Stock Split Calendar (free tool): https://wiseek.ai/split-calendar/
- Live Filing Impact Tracker (rolling 90-day data): https://wiseek.ai/research/filing-impact-index/
- Scored market news: https://wiseek.ai/news/
- Ticker pages (about 6,800): https://wiseek.ai/ticker/
- Plain-English filing explainers: https://wiseek.ai/filings/

Questions or corrections: [wiseek.ai/contact](https://wiseek.ai/contact/)
