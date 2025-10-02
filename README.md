# GoogleEmergentHackathon
# Research Accessibility and Bias Generator

**LINK TO WEBSITE:** https://paper-analyzer-1.preview.emergentagent.com/

## Overview

The Research Accessibility and Bias Generator is an AI-powered system designed to help researchers efficiently evaluate potential bias in academic papers. Instead of providing subjective bias scores, the system performs comprehensive analysis and presents objective, verifiable data points, empowering users to make their own informed conclusions about research reliability.

## Problem Statement

Researchers often struggle to efficiently measure author bias from research papers on a scale relevant to their specific research topics. Traditional manual review processes are time-consuming and may miss subtle indicators of bias or conflicts of interest.

## Solution

Our system provides:

- **Stance and Framing Analysis**: Detects positive, negative, and neutral language patterns within a sophisticated language tree structure, moving beyond simple sentiment analysis
- **Hype Detection**: Critically compares the language and tone of abstracts versus methods sections to flag potentially overstated results
- **Conflict of Interest (CoI) Data Collection**: Researches and lists objective, verifiable data points regarding potential conflicts of interest from authors' public backgrounds (funding sources, affiliations, etc.)

## Target Audience

- College students learning to navigate research bias evaluation
- PhD students with limited experience in conducting data analytics
- Anyone interested in performing quick research analysis

## Core Analysis Methods

The system performs three key types of analysis on research papers:

1. **Stance and Framing Analysis** on the full text of selected papers
2. **Hype Detection** through abstract vs. methods section tone comparison
3. **Conflict of Interest Data Collection** from public databases and author profiles

## User Flows

### 1. The Deep Dive Researcher Flow
*For PhD students and advanced users*

**Input and Scope:**
- Research topic (e.g., "Impact of sugar-sweetened beverages on cardiovascular health")
- Time frame filter
- Source preference filter (e.g., "peer-reviewed journals only")

**Interactive Dashboard:**
- **Stance Distribution**: Visual breakdown (e.g., 40% Positive, 30% Negative, 30% Neutral)
- **Hype Flag**: Severity indicator (High, Medium, Low)
- **Verifiable CoI Points**: Count of flagged items (e.g., 3 data points found)

### 2. The Focused Learning Flow
*For college students and novice researchers*

**Target Paper Selection:**
- Input research topic
- Input specific Paper URL or DOI (e.g., a class-assigned paper)

**Guided Analysis Prompt:**
The system asks: *"What are you most interested in evaluating?"*
- A) Potential exaggeration of findings (Hype)
- B) Subjective language patterns (Stance/Framing)
- C) Author background (CoI)

Users can select one or multiple options.

**Dashboard Bias Walkthrough:**

- **Stance/Framing Tutorial**: Highlights 3-5 sentences with the strongest stance, prompts reflection with questions like: *"How might this specific word choice influence a reader's perception of the results?"*
- **Hype Flag Explanation**: Displays abstract and methods sections side-by-side, highlighting discrepancies in language tone and asking users to identify the disconnect
- **CoI Data**: Provides a streamlined list of conflict of interest data points without interpretation

**Summary Screen:**
Instead of providing a bias score, the system generates an interactive summary: *"You identified 3 instances of strongly positive language, noted the system's High Hype flag, and recorded 2 relevant funding sources. Based on your review, what is your conclusion about the paper's reliability?"*

### 3. The Quick Scan Flow
*For general interest and efficiency-focused users*

**Target Paper Selection:**
- Input research topic

**Bulk Analysis and Filtering:**
1. System simultaneously runs Retrieval, Stance Analysis, Hype Detection, and CoI Data Collection on multiple papers (e.g., 50 papers)
2. Filters results based on user-defined sensitivity (e.g., *"Show me only papers with 'High' Hype Detection OR ≥ 2 verifiable CoI points"*)
3. Presents a refined list (e.g., 12 papers) in card view

**Card View Display:**
Each card shows:
- Paper Title & Authors
- **Top Stance Warning** (e.g., "Overwhelmingly Positive Framing Detected")
- **Highest Severity Flag** (e.g., 🚩 Hype: High)
- **CoI Count** (e.g., 3 Data Points Found)

Clicking the CoI Count reveals the specific objective data points (e.g., affiliation with specific corporation, grant from policy group, board membership).

## Key Features

- **No Subjective Bias Scores**: The system presents objective data, allowing users to draw their own conclusions
- **Educational Approach**: Guides users through the analysis process, building research literacy
- **Scalable Analysis**: From single-paper deep dives to bulk analysis of dozens of papers
- **Transparent Methodology**: Shows users exactly what the system detected and why

## Getting Started

Visit the repository at [https://github.com/aayushi01shah/GoogleEmergentHackathon](https://github.com/aayushi01shah/GoogleEmergentHackathon) for installation instructions and documentation.

---

*Empowering researchers to make informed decisions about research reliability through transparent, objective analysis.*
