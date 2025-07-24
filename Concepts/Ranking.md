# Ranking

## What is ranking in the context of ads?
It is a process of ordering ads for a given user impression based on a scoring function. It determines which ads get shown and in what order. It involves optimizing for relevance, revenue, user experience, and more.

## What factors influence ad rank?
* Bid amount
* Predicted CTR
* Ad relevance (based on user-query/ad matching)
* Landing page quality
* Ad format & extensions
* Ad freshness / user feedback

## How is CTR predicted in real-time for ad ranking?
CTR is predicted using machine learning models trained on historical data, using features like:
* User profile(demographics, past behavior)
* Context(time, device, location)
* Ad features(text, image, format)
* Query/ad match features

## What is the trade-off between relevance and revenue in ranking?
* Prioritizing relevance boosts user satisfaction and long-term engagement
* Prioritizing revenue may yield short-term gain but hurt user trust.
* Most platforms use a blended score (e.g. bid x predicted CTR) to balance both.

## How is ad ranking focuses different in Search Ads vs Display Ads vs Social Ads?
* Search Ads - Query relevance, CTR, landing page
* Display Ads - Context relevance, viewability, bids
* Social Ads - User engagement prediction, personalization

## How can ranking models be improved over time?
* Regularly retrain ML models with fresh click/conversion data
* Use A/B testing to evaluate changes
* Add new features (e.g. device, session history)
* Implement multi-objective learning (relevance + revenue)

## What machine learning models are used for ranking ads?
* Logistic regression (baseline CTR)
* Gradient boosted tress (e.g. XGBoost, LightGBM)
* Deep neutral nets

## What is exploitation vs. exploration?
* Exploitation - show ads that maximize immediate clicks/revenue
* Exploration - occasionally show new/low-data ads to learn their true value