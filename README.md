cny-exchange-rate-analysis
人民币兑美元/欧元历史汇率分析项目
CNY Exchange Rate Analysis (USD & EUR)

1. Problem & User
This project shows how the Chinese Yuan (CNY) changed against the US Dollar (USD) and the Euro (EUR). It helps students, travelers, and small businesses understand exchange rate trends.
 2. Data
- Source: Bank of China (via AKShare library)
- Access date: April 2026
- Key fields: Date, middle rate (converted to 1 foreign currency = CNY)

3. Methods
- Used Python with AKShare to get real data.
- Cleaned data: filled missing values, divided by 100 (original was 100 foreign currency).
- Made three charts: full trend, recent 5 years, yearly average bar chart.

4. Key Findings
- Latest rates: 1 USD ≈ 7.18 CNY, 1 EUR ≈ 7.69 CNY.
- USD/CNY range: 6.84 – 7.23. EUR/CNY range: 7.32 – 8.09.
- Euro fluctuates more than US Dollar.
- Data covers less than 5 years, so long-term trend is limited.

6. Product Link / Demo
【https://www.bilibili.com/video/BV1JJohBFEgj/?spm_id_from=333.1387.homepage.video_card.click&vd_source=da3872011f2ffeb0be9ddeaf376d7af0】

7. Limitations & Next Steps
-Short time span (only recent years). Next: get longer data from SAFE.
-Only middle rate used. Next: add high/low and moving averages.
-No interactive features. Next: build a Streamlit app.

## 5. How to Run
```bash
pip install -r requirements.txt
jupyter notebook ACC102_Track2_CNY_Analysis.ipynb
