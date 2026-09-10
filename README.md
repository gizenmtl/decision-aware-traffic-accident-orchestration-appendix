# Supplementary Materials for Decision-Aware Traffic Accident Orchestration

This repository provides supplementary material associated with the manuscript:

**“A Decision-Aware Hierarchical Multi-Model Orchestration Framework for Explainable and Consistent Multi-Output Traffic Accident Severity Prediction.”**

## Supplementary Table S1 — Complete Feature Dictionary

The complete feature dictionary used in the final modeling framework is available here:

[`Supplementary_Table_S1_Feature_Dictionary.pdf`](supplementary_materials/Supplementary_Table_S1_Feature_Dictionary.pdf)

Supplementary Table S1 documents the processed variables considered in the study, including their English descriptions, feature families, model-branch usage, availability within the intended prediction setting, and predictor/target/exclusion status.

## Intended Prediction Setting

The framework is designed for **post-crash police-record-based assessment**, rather than pre-crash forecasting or pre-hospital triage.

The underlying data consist of police-reported information recorded after a traffic crash has occurred. Therefore, roadway, vehicle, driver, crash-scene, and involved-road-user descriptors available during post-crash record preparation may be used as model inputs.

The indicators reported in the revised manuscript as **“Road-User Type: Passenger”** and **“Road-User Type: Pedestrian”** identify the role of an individual involved in the crash. These one-hot indicators do not encode injury status, fatality status, or the number of injured or deceased persons.

Variables directly encoding the modeled injury/fatality outcomes, their counts, or target-equivalent information were excluded from the predictor matrices before model development. No missingness indicator derived from an injury or fatality target was used as a predictor.

## Data Availability

The raw police-reported crash dataset cannot be publicly redistributed because it was obtained from the General Directorate of Security of Türkiye under legal and institutional restrictions. This repository therefore provides documentation of the feature space rather than the original crash records.
