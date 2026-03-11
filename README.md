# Personal Mess Food Scoring System

## Overview

This project builds a **personal scoring system to evaluate mess food quality** and compares two approaches:

1. A **hand-crafted weighted scoring formula**
2. A **regression model trained to learn scoring weights**

## Method

First, a simple weighted formula is used to calculate a food quality score based on attributes like taste, portion size, freshness, and variety.

Example:
score = 0.4*(taste) + 0.2*(portion) + 0.2*(freshness) + 0.2*(variety)

Then, the formula is replaced with a **trained regression model** to predict scores from the same features.

## Goal

The goal is to compare **rule-based scoring vs learned model predictions** and analyze which approach produces more stable and consistent results.

## Tech Stack

Python, Pandas, Scikit-learn, Google Colab
