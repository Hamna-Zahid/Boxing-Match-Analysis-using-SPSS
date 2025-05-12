# 🥊 Boxing Match Analysis – Canelo vs Bivol (2022)

This project presents an SPSS-based descriptive and visual analysis of punch-level data from the **Canelo vs Bivol 2022** boxing match. The data is extracted from a broader boxing dataset on Kaggle and focuses exclusively on analyzing fighting patterns, punch types, timing, and strategies used during this specific match.

## 📂 Dataset Source

- **Origin**: Kaggle – [BoxByNumbers Boxing Data](https://www.kaggle.com/datasets/omarrojasnguyen/boxbynumbers-boxing-data)
- **Filtered Subset**: Only **Canelo vs Bivol (2022)** fight data was used.
- **Number of Records**: 1,489 observations
- **Main Variables Used**:
  - `fighter`
  - `punchType`
  - `powerpunchType`
  - `punchPlacement`
  - `punchLanded`
  - `partOfCombo`
  - `counterpunch`
  - `knockdownOrKO`
  - `round`
  - `timestamp`

## 📊 Analysis Overview

The analysis is primarily descriptive, with SPSS used to generate summary statistics and visual charts to highlight fighting styles, punch frequency, and round duration.

### Descriptive Statistics

| Variable   | Count | Min | Max | Mean | Std. Dev |
|------------|-------|-----|-----|------|----------|
| round      | 1489  | 1   | 12  | 6.33 | 3.545    |
| timestamp  | 1489  | 0:01| 3:00| 1:33 | 0:50     |

> Most rounds lasted exactly 3 minutes, confirming standard boxing regulations were followed.

### Visual Insights

1. **Fighter Distribution**:
   - **Bivol** appears more frequently than **Canelo**, suggesting a higher level of activity or more recorded punches in the dataset.

2. **Punch Types**:
   - **Jabs** dominate the punch type distribution, followed by **Powerpunches**.
   - **Holds** are rare, emphasizing their defensive role rather than offensive.

3. **Punch Placement vs Punch Type**:
   - Both **Jabs** and **Powerpunches** are primarily aimed at the **head**.
   - **Holds** are categorized as "N/A" in terms of placement, likely due to their non-striking nature.

4. **Round Duration**:
   - The dataset confirms that each round typically lasts around **3 minutes**, adhering to official boxing rules.

## 💬 Discussion

- **Strategic Use of Jabs**: The jab's dominance reflects its utility in controlling distance, setting up combinations, and scoring.
- **Balanced Offense**: Powerpunches complement jabs, showing that fighters aim to balance speed with impact.
- **Defensive Techniques**: The low number of holds suggests their infrequent use, though they play a crucial defensive role.

## 🧠 Limitations & Future Work

- A large portion of the dataset contains **string-type variables**, limiting complex statistical analysis.
- **Further research** could explore:
  - Clinching techniques and defensive maneuvers
  - Changes in punch strategy across multiple fights
  - Effects of evolving boxing rules on match dynamics

## 📌 Conclusion

This study illustrates the central role of the jab in modern boxing, alongside a strategic balance with power punches. The uniform duration of rounds emphasizes fairness and standardization. However, to deepen understanding, future analyses should incorporate more structured and numeric data formats.
