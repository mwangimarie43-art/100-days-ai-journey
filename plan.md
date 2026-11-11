Project Plan: Local Rainfall-Risk Prediction from ENSO and IOD Signals
Timeline: 3 weeks (Nov 11 – Dec 1, 2026)
Problem
A very strong El Niño and a developing positive Indian Ocean Dipole (IOD) are shaping the October–December (OND) short rains in East Africa. Regional outlooks from ICPAC and national meteorological services are probabilistic and cover wide areas, so a farmer or local office still has to guess what the signal means for one specific area.
This project turns the large-scale ENSO/IOD signal into a calibrated, local estimate of whether OND rainfall will be drier than normal, normal, or wetter than normal, and tests how reliable that estimate has been in past El Niño years.
This work builds on the official forecasts and does not replace them. It is a local post-processing and verification layer, evaluated against simple baselines.
Scope
Area: one Kenyan location or sub-county (to be chosen in Week 1)
Season: OND only
Target: OND rainfall tercile (dry / normal / wet), computed from the observed record
Predictors: Niño 3.4 and IOD values from the months before the season (for example, August–September)
Data
Data
Source
Notes
Rainfall
CHIRPS (1981–2025)
Compute OND totals for the chosen area
ENSO index
Niño 3.4 (NOAA)
Monthly values
IOD index
Dipole Mode Index (NOAA/other)
Monthly values; confirm source in Week 1
Week 1 (Nov 11–17): Scope and data
[ ] Lock the scope: one area, OND season, tercile target
[ ] Create the GitHub repository and a Colab notebook
[ ] Pull CHIRPS rainfall for the chosen area and compute OND totals
[ ] Download Niño 3.4 and IOD indices
[ ] Plot OND rainfall against August–September ENSO and IOD values
Checkpoint: Is there a visible signal? If not, record this as a finding and switch to the rainfall onset-date angle.
Week 2 (Nov 18–24): Model and evaluation
[ ] Baseline: climatology (always predict the long-term odds)
[ ] Model 1: logistic regression
[ ] Model 2: random forest (only if time allows)
[ ] Evaluate with leave-one-year-out cross-validation (about 44 seasons)
[ ] Metrics: Brier score and a reliability diagram
[ ] Hold out the strong El Niño years (e.g., 1997, 2015) and test on them
Checkpoint: A results table showing whether the models beat climatology, reported honestly either way.
Week 3 (Nov 25–Dec 1): Package
[ ] README covering problem, data, method, results and limitations
[ ] Model card stating what the model cannot do
[ ] One-page summary
[ ] Small demo: enter a year's August–September values and get probabilities back
[ ] Prepare a 30-second pitch, including how this differs from ICPAC's forecasts
Checkpoint: Someone else can run the notebook from the README.
Buffer and cut rules
Days 19–21 are slack. If Week 1 or 2 runs over, drop the random forest and keep the baseline and logistic regression. A clean, honest simple model is better than an unfinished complex one.
Known limitations
Very few strong El Niño years exist, so uncertainty will be high.
About 44 seasons is a small sample; results should be read cautiously.
The model finds associations, not causes.
ENSO influence is generally weaker for the March–May long rains, so results for OND do not automatically carry over.
After the 3 weeks (optional)
Record a forecast for the March–May 2027 long rains and check it afterwards.
Extend to additional areas.
Add rainfall onset-date prediction.