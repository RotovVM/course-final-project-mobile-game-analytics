# Project: Mobile Game Analytics

## Overview

This repository contains a complete analytics project based on data from a mobile game.  
The project focuses on three key tasks: calculating user retention, analyzing an A/B test of promotional offers, and designing metrics to evaluate an in-game themed event.

The goal is to demonstrate a full analytical workflow: data loading and preparation, metric calculation, application of statistical methods, and business-oriented interpretation of results.

## Project tasks

1. **Retention calculation**  
   A Python function was implemented to calculate player retention by days since registration.

2. **A/B test analysis**  
   Two sets of promotional offers were compared to determine the more effective option based on product and statistical metrics.

3. **Event metrics design**  
   Metrics were proposed to evaluate the results of the latest themed event in the game.

## Data

The project uses datasets described in the notebook:

- `problem1-reg_data.csv` — user registration timestamps.
- `problem1-auth_data.csv` — user login timestamps.
- A/B test data with user group assignment and revenue.

These datasets are used to analyze user behavior, retention, monetization, and the impact of product experiments.

## Tech stack

The project is implemented in Python with the following libraries:

- `pandas`
- `NumPy`
- `Matplotlib`
- `SciPy`
- `Pingouin`

## Approach (workflow)

At a high level, the work was structured in the following steps:

1. **Data loading and preprocessing**  
   Imported registration and login datasets, aligned timestamp formats, and prepared user-level activity tables.

2. **Retention function implementation**  
   Built a function that calculates day‑by‑day retention from the registration date, tested it on the full dataset and on samples, and visualized the retention curve.

3. **A/B test evaluation**  
   Aggregated key product metrics by test group, checked statistical assumptions, selected appropriate tests, and evaluated whether differences between groups are statistically significant and practically meaningful.

4. **Event metrics design**  
   Identified meaningful behavioral and monetary indicators for the themed event, defined metric formulas, and outlined how they could be used to monitor event performance.

## Results

By the end of the project:

- A reusable retention calculation function with supporting visualizations was implemented.
- The A/B test of promotional offers was evaluated with statistically justified conclusions about which variant performs better.
- A set of metrics for assessing the impact of in‑game events on user behavior and revenue was formulated.

These results can be used as a template for analyzing other mobile games, structuring product experiments, and monitoring event performance.

## Skills demonstrated

The project showcases the following skills:

- calculation and interpretation of retention metrics;
- working with cohort logic and user lifetimes;
- analysis of A/B tests;
- selection and interpretation of product metrics;
- statistical thinking and hypothesis testing;
- analytics in Python;
- visualization of analytical results.

## Attribution

This project is based on educational assignments from the **"Аналитик данных"** course at [karpov.courses](https://karpov.courses).

В соответствии с п. 2.1.10 Оферты [karpov.courses](https://karpov.courses/terms-of-use) учебные задания использованы для формирования портфолио при соблюдении условий указания авторства ООО «Карпов Курсы» и размещения ссылки на сайт karpov.courses. В репозитории отсутствует информация, связанная с доступом к базе данных Курса.
