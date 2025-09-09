# Case Study Title : Robinhood GME Sentiment Analysis 

##  Case Study Overview
This case study investigates **public sentiment, emotions, and discourse evolution** surrounding **Robinhood’s role in the GameStop (GME) short squeeze of January 2021**. Leveraging **Twitter-based text analytics**, the analysis examines how user perceptions shifted **Before, During, and After** the trading restrictions imposed by Robinhood.  

The goal is to generate **evidence-based insights** to inform strategies on **trust rebuilding, crisis communication, and platform improvement** in the wake of reputational and regulatory challenges.  

---

# Author: 
Pratik Ganguli


##  Research Objectives
1. **Sentiment & Emotion Evolution**  
   - Track how **positive, negative, and neutral sentiments** changed across the three phases.  
   - Identify dominant emotions such as **trust, anger, fear, anticipation**, etc.  

2. **Discourse Themes & Topics**  
   - Use **topic modeling, RAKE, and word co-occurrence** to uncover recurring themes.  
   - Compare **investment chatter (Before)** vs. **conflict-driven discourse (During)** vs. **crypto diversification (After)**.  

3. **Crisis & Trust Implications**  
   - Understand user reactions to **trading restrictions** and **institutional references (Citadel, hedge funds, SEC)**.  
   - Recommend **PR, transparency, and app-level improvements** for Robinhood.  

---

##  Methodology
The analysis applied a structured **three-phase text mining pipeline** using the **Enginius Marketing Analytics Platform**:

- **Data Source:** Twitter posts mentioning Robinhood (Jan 12 – Feb 11, 2021)  
- **Phases:**
  - **Before:** Jan 12–21 (baseline investor chatter)  
  - **During:** Jan 22–Feb 1 (peak short squeeze & trading halt)  
  - **After:** Feb 1–11 (post-crisis discourse, crypto shift)  
- **Techniques Used:**  
  - **Word Clouds** – visualize trending terms  
  - **Sentiment Analysis** – classify tweets into positive, neutral, negative  
  - **Emotion Detection** – map to NRC emotion lexicon (trust, anger, joy, fear, etc.)  
  - **Topic Modelling (RAKE, Co-occurrence)** – extract themes across phases  
  - **Parts-of-Speech (POS) Tagging** – study linguistic structure of tweets  

---

##  Key Findings

### Phase 1: **Before the Surge**
- Discourse: Promotional & opportunity-seeking → stocks, trading tips, crypto.  
- Sentiment: **58% positive**, **18% negative**, **24% neutral**.  
- Emotions: **Trust (24%)**, **Anticipation (16%)**, **Anger (12%)**.  
- Interpretation: Users engaged & optimistic, minimal skepticism.  

### Phase 2: **During the Crisis**
- Discourse: Anger-driven → “restrictions,” “halt,” “Citadel,” “hedge funds.”  
- Sentiment: **50% negative**, **31% positive**, **19% neutral**.  
- Emotions: **Fear (16%)**, **Anger (14%)**, **Trust (20%)**.  
- Interpretation: Public backlash intensified; Robinhood perceived as siding with hedge funds.  

### Phase 3: **After the Peak**
- Discourse: Diversified → crypto hype (Dogecoin, Bitcoin) + lingering distrust.  
- Sentiment: **43% positive**, **34% negative**, **22% neutral**.  
- Emotions: **Trust (23%)**, **Anticipation (16%)**, **Fear (13%)**, **Anger (12%)**.  
- Interpretation: Partial sentiment recovery, but trust erosion persisted.  

---

##  Strategic Insights

###  For Robinhood
- **Revenue & Trust Balance:** Communicate collateral and settlement constraints transparently.  
- **PR Strategy:** Address fairness concerns directly during congressional hearings.  
- **Platform Improvements:** Add **trade alerts, settlement timelines, & education prompts**.  

###  For Regulators
- Enhanced oversight on **Payment for Order Flow (PFOF)** and **market fairness** disclosures.  

###  For Users & Investors
- Caution against **platform dependence**; importance of understanding **settlement mechanics**.  

---

##  Tools & Techniques
- **Enginius** – Text analytics (sentiment, emotion, topic modeling)  
- **Corpus:** For sentiment and emotion analysis, the **Eniginius inbuilt corpus** was utilized. No external lexicons (e.g., NRC, Bing) were applied in this case study.
- **Analytics Methods:** Word Clouds, RAKE, Co-occurrence, Topic Modeling, POS Tagging  

---

##  Repository Contents
- `Robinhood_GME_Sentiment_Analysis_Report_2025.pdf` – Full case study report  
- `Robinhood_GME_Executive_Slides_2025.pdf` – Executive summary for business stakeholders  
- `Twitter_Sentiment_Data.csv` – Processed dataset (if shared)  
- `Notebooks/` – Quarto or R scripts for sentiment analysis (if replicated outside Enginius)  

---

##  Acknowledgement
- This case study was completed as part of a **Master’s program project at the **[University of Auckland](https://www.auckland.ac.nz/en.html)**.  
- Special thanks to **Enginius Marketing Analytics** for providing the platform to conduct advanced text analytics.  
- Data sourced from **Twitter** (publicly available posts, 2021).  

---

## 📝 Citation
Ganguli, P. (2025). *Public Sentiment Analysis of Robinhood Across the GameStop Episode: A Twitter-Based Text Analytics Case Study.* University of Auckland.  
