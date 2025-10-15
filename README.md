
# **PRISM Insurance Dashboard**

## **Project Overview**
This Power BI project analyzes a comprehensive insurance dataset to uncover patterns in premiums, claims, and customer demographics. The goal is to identify profitability risks, improve claim management, and guide business strategy.

The workflow followed a complete **data pipeline**:
- **Loaded CSV file into SQL** for initial storage and querying.
- **Performed minor data cleaning in SQL** (fixing inconsistencies, correcting formats, handling nulls).
- **Loaded cleaned data into Power BI** for modeling, calculations, and interactive visualizations.

The dashboard is designed with two interactive pages:
- **Sheet 1:** A high-level KPI summary with visual insights into policy performance, claim trends, and customer segments.
- **Sheet 2:** A **drill-through view** showing all related records filtered dynamically by **Claim Status, Policy Type, and Gender**, enabling deeper, record-level analysis.

---

## **Data Source**
- **Source:** Kaggle (sample insurance dataset)
- **Rows:** ~10,000 records
- **Policy Types:** Travel, Health, Auto, Life, Home
- **Age Groups:** Young Adult, Adult, Elderly (calculated via DAX measures)

---

## **KPIs Measured**
- Total Premium Collected – ₹5.98M
- Total Coverage Amount – ₹600.55M
- Total Claim Amount – ₹16.91M
- Loss Ratio – 2.83
- Claim Status Counts – Settled, Pending, Rejected
- Average Premium – ₹0.6K
- Average Claim Amount – ₹1.69K

---

## **Dashboard Features**
- Interactive slicers for Claim Status, Policy Type, and Gender
- Drill-through to view detailed customer and policy data
- Policy type breakdown for premium, coverage, and claims
- Claim amount distribution by Age Group
- Gender-based segmentation analysis
- Loss ratio calculation for profitability insights

---

## **Executive Insights**
- **Travel Insurance** is the top revenue generator (₹2.5M) but carries high pending (₹5.7M) and rejected (₹10.7M) claims — a profitability risk.
- **Adults** account for the highest claim payouts (₹7.4M), suggesting higher usage or risk.
- **Loss Ratio** at 2.83 shows claims are almost 3× the premium collected — unsustainable in the long term.
- **Claim Rejections** (4.4K) outpace Settlements (3.4K), especially in Travel and Health policies, potentially damaging customer trust.
- **Gender Distribution** is balanced (Male: 5003, Female: 5001), so segmentation efforts should focus on age and policy type instead.

---

## **Final Recommendations**
- **Reprice High-Risk Segments:** Adjust premium rates for adult customers and high-claim policy types (especially Travel).
- **Reduce Claim Rejections:** Simplify claim documentation, improve customer communication, and strengthen verification processes.
- **Enhance Risk Controls:** Introduce stricter underwriting rules and fraud detection for Travel and Health policies.
- **Diversify Revenue Sources:** Promote Health and Auto policies to reduce overreliance on Travel insurance.
- **Targeted Campaigns:** Create awareness programs for Young Adults to increase policy uptake in this lower-claim group.

---

## **Conclusion**
The analysis of PRISM Insurance’s portfolio reveals a strong revenue base driven by Travel insurance, but profitability is under pressure due to high claim volumes, particularly in adult customers and high-risk policy types. A loss ratio of 2.83 signals that current pricing and underwriting strategies require immediate recalibration. Elevated claim rejection rates, especially in Travel and Health segments, pose a risk to customer satisfaction and retention. By implementing targeted premium adjustments, streamlining claim processes, and diversifying product focus toward lower-risk segments like Auto and Young Adults, the company can strengthen financial performance while maintaining market competitiveness. Continuous monitoring of these KPIs will be critical for sustainable growth.

---

## **Tools Used**
- **SQL** – Imported CSV file, performed initial data cleaning and minor transformations.
- **Power BI Desktop** – Data modeling, DAX calculations, and visualization creation.
- **DAX Measures** – Age group classification, KPI calculations (Loss Ratio, Averages, etc.).
- **Data Modeling** – Defined relationships between claims, policies, and customers for accurate analysis.

---

## **How to Use**
- Use slicers on Sheet 1 to filter by Claim Status, Policy Type, and Gender.
- Right-click a visual and use Drill-through to open Sheet 2 for detailed records.
- Hover over charts to see additional data tooltips.

---

## **Author**
**Shivaram Adabala**
