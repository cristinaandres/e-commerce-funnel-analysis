# e-commerce-funnel-analysis
Exploratory data analysis of an e-commerce conversion funnel using Google Sheets to identify drop-off points and optimize UX.

## 📌 Business Context
An e-commerce company wants to understand where they are losing potential customers during the purchase process and whether this drop-off varies by device or acquisition channel. The goal is to prioritize UX/UI improvements and optimize marketing spend.

## 🛠️ Methodology
- Analyzed a dataset of **120,000 user sessions**.
- Used **Google Sheets** to clean, aggregate, and analyze the data.
- Calculated stage-to-stage conversion rates and drop-off volumes using `COUNTIF` and `COUNTIFS` functions.
- Segmented the funnel by **Device** (Mobile vs. Desktop) and **Acquisition Channel** (Organic, Paid Ads, Social, Email).

## 💡 Key Findings
1. **The Major Bottleneck:** The most significant drop-off occurs between "Viewed Product" and "Added to Cart," where over **65% of users abandon**.
2. **Device-Agnostic Friction:** Conversion rates across all funnel stages are virtually identical between Mobile and Desktop users. The mobile experience is not the sole culprit.
3. **Channel-Agnostic Friction:** Users from all acquisition channels (Paid, Organic, Social, Email) exhibit the exact same behavioral patterns and drop-off rates.

## 🚀 Recommendations
- **Structural Issue:** The data proves the friction is universal. The problem lies in the Product Detail Page (PDP) or checkout process itself, not in the traffic quality or device type.
- **UX/UI Audit (A/B Testing):** Conduct A/B tests on the product page to improve the Call-to-Action (CTA), display shipping costs earlier, and enhance product imagery.
- **Marketing Strategy:** Pause aggressive paid acquisition campaigns temporarily. Sending users to a highly leaky funnel is inefficient; fix the conversion rate first.

## 🧰 Tools Used
- Google Sheets (Data Aggregation, COUNTIFS, Visualization)
