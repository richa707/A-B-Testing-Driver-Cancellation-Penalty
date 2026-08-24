# Driver Cancellation Penalty: Causal Inference & A/B Test

A three-variant A/B test measuring the causal impact of a driver cancellation penalty on driver behavior and platform profit — designed to give leadership a clear, data-backed recommendation on whether (and how much) to charge drivers who cancel accepted rides.

## Problem

Ride-hailing platforms lose money and rider trust when drivers cancel accepted trips. Charging a cancellation penalty could reduce cancellations and protect profit — but it could also push drivers toward frustration and attrition, hurting driver supply longer-term. Leadership needed to know: does a penalty actually help, and if so, how large should it be?

## Experiment Design

- **Structure**: Six-week, three-variant randomized experiment across drivers, testing penalty amounts of **$0 (control) / $10 / $20** per cancellation.
- **Metrics**: Cancellation rate, actual vs. expected profit by variant, and driver-level behavior segments.
- **Method**: Hypothesis testing and regression with controls to isolate the causal effect of the penalty from confounding factors (e.g., driver tenure, market, time-of-day mix).

## Analysis

- Modeled actual vs. expected profit by variant and by driver segment to see not just whether the penalty "worked" on average, but where it worked and where it backfired.
- Weighed the short-term profit gain from reduced cancellations against the longer-term risk of driver attrition — since a penalty that boosts this month's profit but drives experienced drivers off the platform can be a net loss.

## Outcome

Delivered a CEO-level recommendation on penalty strategy, explicitly balancing short-term revenue impact against long-term driver retention risk, rather than optimizing for profit alone.

## Tech Stack

Python (pandas, statsmodels/scipy), SQL, A/B testing & causal inference methods

## Notes

Underlying trip/driver data is not included in this repo. Reach out for a walkthrough of methodology or the full write-up.
