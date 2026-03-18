**2026 March Madness Predictor**
Authors: Frank McLaughlin and Jonah Simonson

**Organization**: UW Madison Sports Analytics Club

**Challenge**: March Madness Data Challenge 2026

**Project Overview**
This project uses 24 years of historical NCAA Tournament data (2002–2025) to predict the outcomes of the 2026 tournament. Using a combination of efficiency metrics and historical rankings, we built a Random Forest model to estimate the win probability for every possible 2026 matchup.

**Data Sources**
We integrated three  data sets to build our feature set:

KenPom/DEV Efficiency Stats: This includes adjusted tempo, offensive/defensive efficiency, and shooting stats.

Kaggle March Mania 2026: Historical game results, seeds, and regular-season records used for training and ground-truth validation.

Massey Ordinals: Specifically utilized KenPom rankings to provide a pre-tournament snapshot of team strength.

**AI Disclosure & Usage**
We utilized Claude in the following ways:

Data Cleaning & Mapping: Claude helped in the tedious process of cross-referencing team names between datasets

Bracket Simulation Logic: Claude was used to help draft the logic in Step 9, ensuring a clean, formatted terminal output for the regional simulations and the Final Four bracket progression.
