# Submission

Complete this file in your fork before submitting.

## Team

- Team name: TrendFin(h)er
- Team members: Morena, Marija, Ashton, Maria
- GitHub fork URL: 
- Demo URL, if any:
- Video walkthrough URL, if any:

## Summary

We help category managers decide what to test, buy, launch, or monitor next by collecting messy signals, cleaning and scoring them, and turning them into ranked opportunities with clear actions.


## How To Run

Include exact setup and run commands.

```bash
# Example: Open up two terminals: on the first one "make api" and on the other one "make web"
# npm install
# npm run dev
```

## Inputs

Describe the inputs your system uses. The list below is a set of examples, not mandatory fields; keep, remove, or replace them with the inputs that actually apply to your solution.

- Market: Swiss Outdoor retail
- Category: NA
- Data Sources: competitor assortment, Youtube, TikTok, Google Trends, market data
- Languages: English
- APIs: OpenAI

## Outputs

Describe the main output artifacts in this repository or linked from it.

- Dashboard or UI: 
- Report:
- Structured data:
- API endpoint: 
- Screenshots or visuals:<img width="2444" height="1120" alt="image" src="https://github.com/user-attachments/assets/766c9955-9506-4f35-94cc-f26817dd7bff" />


## Ranked Opportunities

Teams are free to decide what counts as evidence and how they want to score confidence. Be creative, as long as the result is understandable.

| Rank | Opportunity | Evidence | Confidence |
| --- | --- | --- | --- |
| 1 |  |  |  |
| 2 |  |  |  |
| 3 |  |  |  |

## Evidence Trail

Primary research: conversation with the Global Category Management team at Intersport, used both to confirm the problem and to react to Scout's top recommendations. 
Mocked source set inside the app: each opportunity links its underlying sources with market and date.

## Reusability

The engine is category- and market-agnostic. Nothing in the scoring model is specific to outdoor. Swap the seed keywords, source set, and the same pipeline runs for another retailer, category, or industry.

## Known Limitations

Data is mocked for the demo. A production version needs live source ingestion and deduplication.
Validation rests on one retailer (Intersport). Precision and lead time are demonstrated on a worked example, not measured across a backtested set.
The transferability call (does this cross into CH/DACH) is currently a reasoned heuristic, not a fitted model.
No live scoring of new signals yet. The four-axis scores are authored, not computed from raw source data.
Next steps: connect at least one real source, backtest lead time against historical POS to put a number on precision, and tighten the transferability logic with market-specific inputs.

## Architecture Notes

Briefly describe the main components of your solution and how data flows between them.
