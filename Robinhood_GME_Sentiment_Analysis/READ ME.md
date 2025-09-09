# Case Study Title: Public Sentiment Analysis of Robinhood Across the GameStop Episode

## Case Study Overview
This case study examines **user sentiment and discourse surrounding Robinhood during the GameStop (GME) stock surge in January 2021** using **Twitter-based text analytics**. Robinhood faced intense public scrutiny after restricting trading in GME and other volatile stocks, leading to questions about platform transparency, investor trust, and operational fairness.

The study analyzes Twitter data across three phases—**Before**, **During**, and **After** the peak of the GME surge—to uncover trends in sentiment, emotions, and conversation topics. Insights are used to guide **strategic communication, platform modifications, and trust restoration measures**.

**Author:** Pratik Ganguli  
**Date:** August 16, 2025  
**University:** University of Auckland  

---

## Table of Contents

1. [Problem Statement](#problem-statement)  
2. [Purpose of the Report](#purpose-of-the-report)  
3. [Methodology](#methodology)  
   - [Data Collection](#data-collection)  
   - [Text Analytics Techniques](#text-analytics-techniques)  
   - [Phase Setup](#phase-setup)  
4. [Analysis and Results](#analysis-and-results)  
   - [Phase 1: Before the Surge](#phase-1-before-the-surge)  
   - [Phase 2: During the Surge](#phase-2-during-the-surge)  
   - [Phase 3: After the Surge](#phase-3-after-the-surge)  
5. [Recommendations](#recommendations)  
6. [Conclusion](#conclusion)  
7. [Exhibits](#exhibits)  
8. [Repository Contents](#repository-contents)  
9. [Acknowledgement](#acknowledgement)  
10. [Citation](#citation)  

---

## Problem Statement

In January 2021, **Robinhood**, a mobile trading platform aiming to democratize finance, became central to a retail-driven **short squeeze on GameStop (GME)** stock. Key issues included:

- Restriction of trading in GME and other volatile stocks  
- Public perception of bias favoring hedge funds over retail investors  
- Negative media coverage, social media backlash, and regulatory scrutiny  
- Operational vulnerabilities in settlement and liquidity infrastructure  
- Concerns about gamified features encouraging risky trading  

Robinhood needed **data-driven insights** to understand user sentiment, emotion, and thematic discourse across the three critical phases of the GME episode.

---

## Purpose of the Report

This report aims to provide **actionable insights** for Robinhood by:

1. Tracking **evolution of user sentiment and emotions** across Before, During, and After phases  
2. Identifying **dominant topics and themes** in public conversations  
3. Guiding **strategic PR, app modifications, and operational transparency** initiatives  
4. Recommending steps to **restore trust, mitigate reputational risk, and enhance platform credibility**

---

## Methodology

### Data Collection

- **Platform:** Twitter  
- **Timeframes:**  
  - Before: Jan 12–21, 2021  
  - During: Jan 22–Feb 1, 2021  
  - After: Feb 1–11, 2021  
- **Stop words:** Default + "Robinhood"  
- **Sample Size:** ~15,000 tweets across all phases  
- **Categorization:** Tweets divided by phase for temporal analysis  

### Text Analytics Techniques

- **Word Cloud Analysis:** Identifying high-frequency terms  
- **Sentiment Analysis:** Categorizing tweets as Positive, Neutral, Negative  
- **Emotion Detection:** Mapping tweets to emotions (trust, anticipation, anger, etc.)  
- **Parts-of-Speech (POS) Tagging:** Understanding grammatical structure and user focus  
- **Topic Modeling:** Identifying key discussion themes (5 topics per phase)  

### Phase Setup

| Phase       | Dates           | Objective                                 |
|------------|----------------|-------------------------------------------|
| Before     | Jan 12–21      | Baseline sentiment and discourse          |
| During     | Jan 22–Feb 1   | Crisis response, trading restrictions     |
| After      | Feb 1–11       | Post-crisis sentiment recovery & trends  |

---

## Analysis and Results

### Phase 1: Before the Surge

- **Word Cloud:** High-frequency terms include `stock, free, join, link, traders, stockstobuy, crypto, bitcoin`  
- **Sentiment Distribution:** Positive 58%, Neutral 24%, Negative 18%  
- **Emotion Breakdown:** Trust 24%, Anticipation 16%, Anger 12%, Joy 11%  
- **POS Analysis:** Nouns 31%, Verbs 23%, Adjectives/Adverbs 8%  
- **Interpretation:** Largely positive and community-focused discourse emphasizing stock promotion, engagement, and opportunity-seeking  

---

### Phase 2: During the Surge

- **Word Cloud:** Key terms: `gme, gamestop, amc, trading, suspend, halt, citadel, hedge, ceo`  
- **Sentiment Distribution:** Negative 50%, Neutral 19%, Positive 31%  
- **Emotion Breakdown:** Trust 20%, Fear 16%, Anger 14%, Anticipation 13%  
- **POS Analysis:** Focus shifted toward actors, restrictions, and conflict; verbs indicate action and accusations  
- **Interpretation:** Discourse shifted to frustration, distrust, and scrutiny of institutional actors; sentiment and emotions became volatile  

---

### Phase 3: After the Surge

- **Word Cloud:** Terms include `stock, gamestop, dogecoin, free, join, trading, restrictions, wallstreetbets, ceo`  
- **Sentiment Distribution:** Positive 43%, Neutral 22%, Negative 34%  
- **Emotion Breakdown:** Trust 23%, Anticipation 16%, Fear 13%, Anger 12%  
- **POS Analysis:** Consistent grammatical pattern; adjectives/adverbs richer, reflecting broader discussion of crypto, residual anger, and platform trust  
- **Interpretation:** Sentiment partially recovered; user focus diversified beyond GME to crypto and ongoing platform concerns  

---

## Recommendations

1. **Strategic PR & Communication:**  
   - Address trading restrictions and platform transparency  
   - Educate users on PFOF, settlement processes, and risk management  
   - Deploy campaigns via social media to rebuild trust  

2. **App Improvements:**  
   - Trading alerts, enhanced notifications, educational prompts for first-time investors  
   - Transparent settlement timelines  

3. **Operational Transparency:**  
   - Centralized information portal for users and regulators  
   - Continuous monitoring of social media sentiment to identify misinformation  

**Goal:** Restore trust, mitigate reputational risk, and demonstrate a responsible, user-focused approach  

---

## Conclusion

Twitter analysis highlights rapid evolution of public sentiment during the GME episode:

- **Before:** Positive, opportunity-driven discourse  
- **During:** High negativity, anger, and fear; focus on institutional scrutiny  
- **After:** Partial recovery with diversified conversation on crypto and platform safety  

Proactive PR, app enhancements, and operational transparency are critical for **trust restoration and future crisis management**.

---

## Exhibits

**Before Phase:**  
- Exhibit A1 – Word Cloud  
- Exhibit A2.1 – Sentiment Distribution  
- Exhibit A2.2 – Valence Histogram  
- Exhibit A3.1 – Emotion Distribution  
- Exhibit A3.2 – Emotion Pie Chart  
- Exhibit A4 – Topic Model Results  
- Exhibit A5 – POS Distribution  

**During Phase:**  
- Exhibit B1 – Word Cloud  
- Exhibit B2.1 – Sentiment Distribution  
- Exhibit B2.2 – Valence Histogram  
- Exhibit B3.1 – Emotion Distribution  
- Exhibit B3.2 – Emotion Pie Chart  
- Exhibit B4 – Topic Model Results  
- Exhibit B5 – POS Distribution  

**After Phase:**  
- Exhibit C1 – Word Cloud  
- Exhibit C2.1 – Sentiment Distribution  
- Exhibit C2.2 – Valence Histogram  
- Exhibit C3.1 – Emotion Distribution  
- Exhibit C3.2 – Emotion Pie Chart  
- Exhibit C4 – Topic Model Results  
- Exhibit C5 – POS Distribution  

---

## Repository Contents

- `READ ME.md` – Repository documentation and case study details  
- `RobinhoodCaseAnalysis_.pdf` – Initial uploaded case study file  
- `Robinhood_Case_Study_.pdf` – Final full case study report
  
---

## Acknowledgement

- Completed as part of a **Master’s program project** at the **[University of Auckland](https://www.auckland.ac.nz/en.html)**  
- Thanks to **Enginius Marketing Analytics** for simulation tools  
- Data sourced from **Twitter API and curated datasets for GME-related discussions**  

---

## Citation

Ganguli, P. (2025). *Public Sentiment Analysis of Robinhood Across the GameStop Episode: Twitter-Based Text Analytics for User Emotions and Platform Trust.* University of Auckland.

---

