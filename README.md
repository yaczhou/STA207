# STA207 — Can Smaller Classes Close the Achievement Gap?

Analyzed the impact of class size on student achievement using the Tennessee STAR randomized education experiment. Applied regression modeling, matching methods, and causal inference techniques to study achievement gaps across demographic and socioeconomic groups, and investigated whether smaller classes improve academic outcomes in early education.

---

## Overview

This project analyzes data from Project STAR (Student/Teacher Achievement Ratio), one of the largest randomized education experiments conducted in the United States. The study investigates whether smaller class sizes improve early reading outcomes and whether these effects differ across demographic and socioeconomic groups.

Using statistical modeling, matching methods, and causal inference techniques, the analysis estimates the impact of classroom size on student achievement in kindergarten and first grade.

---

## Abstract

Project STAR was a large-scale randomized education experiment conducted in Tennessee during the 1980s. Students entering kindergarten were randomly assigned within schools to one of three classroom types:

* Small classes
* Regular classes
* Regular classes with a teacher’s aide

Because treatment assignment occurred randomly within schools, the experiment allows causal effects of class size on academic outcomes to be estimated.

This project studies reading performance as the primary outcome variable and analyzes whether smaller class sizes improve academic achievement while controlling for demographic and socioeconomic factors such as race, free-lunch status, and school-level variation.

Regression models, mixed-effects ANOVA, and matching-based sensitivity analyses were implemented to evaluate treatment effects and investigate achievement gaps across student populations.

The results show that students assigned to smaller classes generally achieve higher reading scores than students in regular classrooms. However, socioeconomic status remains a strong predictor of educational outcomes, suggesting that smaller class sizes improve performance but do not completely eliminate achievement inequalities.

---

## Research Questions

### Primary Question

Does assignment to smaller classes causally improve student achievement?

### Secondary Question

Do students from disadvantaged socioeconomic backgrounds benefit more from smaller classes?

---

## Methods

The analysis includes:

### Data Cleaning

* Removed missing observations
* Processed longitudinal student records
* Constructed reading-score outcomes

### Exploratory Data Analysis

* Examined score distributions
* Verified treatment balance across groups
* Compared demographic characteristics

### Statistical Modeling

* Mixed-effects ANOVA
* Linear regression models
* School-level random effects
* Interaction analysis for demographic factors

### Sensitivity Analysis

* Matching methods using propensity scores
* Change-in-score models
* Robustness checks across treatment groups

---

## Key Findings

* Students in smaller classes perform better on average.
* Reading-score improvements increase from kindergarten to first grade.
* Socioeconomic status remains a strong predictor of student performance.
* School-level variation contributes substantially to achievement differences.
* Smaller class sizes improve educational outcomes but do not fully eliminate achievement gaps.

---

## Tools Used

This project was implemented in R using:

* tidyverse
* ggplot2
* lme4
* emmeans
* MatchIt
* plotly

---

## Authors

* Kayla Yu Chen
* Jack La
* Matthew Martinez
* Kevin Zhou
