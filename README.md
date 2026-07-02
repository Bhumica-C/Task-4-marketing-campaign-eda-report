# Marketing Campaign EDA Report

## Project Overview
This project analyzes a marketing campaign dataset to answer a key business question:

**Which marketing channels deliver the best ROI, and where should budget be allocated?**

The dataset includes campaign details such as impressions, clicks, leads, conversions, cost, and revenue. Using Python (Pandas, Matplotlib, Seaborn) in Google Colab, the analysis explores performance across channels and identifies actionable recommendations.

---

## Dataset
**Columns:**
- CampaignID
- StartDate, EndDate
- Channel
- Impressions, Clicks, Leads, Conversions
- Cost_USD, Revenue_USD
- ROI

---

## Analysis Steps
1. **Data Cleaning**
   - Converted date columns to datetime format
   - Checked for missing values and duplicates
   - Ensured numeric columns were properly typed

2. **Visualizations**
   - Conversions by Channel (bar chart)
   - ROI by Channel (bar chart)
   - Marketing Funnel (Impressions → Clicks → Leads → Conversions)
   - Cost vs Revenue (scatter plot)
   - Monthly Conversions Trend (line chart)

3. **Insights**
   - Search Ads had the highest ROI despite fewer impressions
   - Social Media generated high impressions but poor ROI
   - Major drop-off occurred between Clicks → Leads, suggesting landing page optimization is needed
   - Conversions peaked in Q2, indicating seasonal effects

---

## Recommendations
- Increase spend on high-ROI channels (Search Ads)
- Reduce budget for low-performing channels (Social Media)
- Optimize landing pages to improve conversion from Clicks → Leads
- Test new creatives for Email campaigns to boost engagement

---

## 📂 Repository Structure
marketing-campaign-eda-report/
│── data/                # Raw dataset (CSV)
│── notebooks/           # Colab notebook with analysis
│── visuals/             # Exported charts (PNG)
│── README.md            # Project documentation


---

## 🚀 How to Run
1. Clone the repository
2. Open the notebook in Google Colab
3. Upload the dataset to `/data`
4. Run all cells to reproduce analysis and charts

---

## 📸 Sample Visuals
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/944c6e84-328c-4fb0-bb14-47b0e36f6840" />
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/18c616e0-9c38-42b8-a867-6b3a50dd8752" />
<img width="547" height="506" alt="image" src="https://github.com/user-attachments/assets/98b1bfa0-d106-40a1-80fc-ba27cc5a0293" />
<img width="589" height="455" alt="image" src="https://github.com/user-attachments/assets/ab514ce3-51c7-4d02-ad66-1ffee5c0654d" />
<img width="591" height="471" alt="image" src="https://github.com/user-attachments/assets/053204f1-ecc0-44e9-8b11-f0c6bc144a44" />


---

## ✨ Author
Prepared by **Bhumica C** as part of a Data Analyst internship project.  
