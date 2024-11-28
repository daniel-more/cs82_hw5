### Trends in U.S. Presidential Debates, 1960-2020  
**Daniel More Torres & Michael Assmus**

**Hypotheses:**  
1. Debate language has become more negative, especially in the last 15 years.  
2. Similar topics dominate debates today as in 1960.  
3. Clustering can identify topics or party distinctions with minimal data manipulation.  

**Data:**  
The analysis used the *USAPresidentialDebates: 2-Party USA Presidential Debate Transcripts (1960-2020)* dataset by Reilly et al. It includes transcripts from all two-party presidential debates, split into uninterrupted speech passages, along with contextual data (date, speaker, party, economic indicators). Short, incoherent passages were excluded.  

**Findings:**  
1. **Sentiment Analysis:**  
   - Debate language has mostly been more positive than negative.  
   - Republicans generally used more positive language than Democrats, except in 1980 (Republican dip) and post-2008, when Democrats became more positive.  
   - The last 15 years show an overall negativity increase, particularly in 2020.  
   - Economic anomalies (e.g., high inflation in 1980) may explain some trends, though no clear cause was found for recent negativity.  

2. **Topic Analysis:**  
   - Using Latent Dirichlet Allocation, passages were grouped into three broad topics:  
     1. **Leadership & Foreign Policy**  
     2. **Social Justice & Crime**  
     3. **Climate Change & Economy**  
   - Topics today are not the same as in 1960, and their relative importance has shifted significantly over time.  

3. **Clustering Analysis:**  
   - Clustering did not reliably distinguish parties or topics. Instead, clusters aligned with debate years, likely reflecting shifting terminology and issue focus. Interestingly, passages from 2020 resembled both the 2016 election and debates from 1960.  

**Conclusions:**  
- Language has become more negative, but the trend is exaggerated by recent extremes and historical context.  
- Debate topics have changed significantly since 1960, challenging the second hypothesis.  
- Clustering revealed temporal patterns, suggesting that debates reflect the language and issues of their time rather than static divisions by topic or party.