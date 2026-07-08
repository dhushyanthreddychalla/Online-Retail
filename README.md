📊 Retail Customer Analytics — RFM Segmentation Dashboard

An interactive, front-end analytics dashboard that performs Customer Segmentation and RFM (Recency, Frequency, Monetary) Analysis on the UCI Online Retail Dataset — 541K+ real-world e-commerce transactions from a UK-based online retailer.

The dashboard turns raw transactional data into actionable business insight: who your best customers are, who's at risk of churning, and how revenue trends over time — all inside a single, self-contained, dependency-light web app.

🔗 Live Demo: [online-retail-vert.vercel.app]


✨ Features


📈 KPI Overview — Total revenue, transaction count, active customers, and top revenue-generating country at a glance
📊 Revenue Trend Chart — Month-over-month revenue growth (Dec 2010 – Dec 2011) via Chart.js
🌍 Country-wise Revenue Breakdown — Visual split of revenue contribution by country
🧩 Customer Segmentation — Customers grouped into 5 RFM-based segments: Champions, Loyal Customers, Potential Loyalists, At Risk, and Lost Customers — each with a tailored retention strategy
🔍 Customer Explorer Table — Live search, filter, sort, and pagination across the customer base
🎛️ RFM Score Simulator — Interactively adjust Recency, Frequency, and Monetary inputs to see which segment a hypothetical customer falls into in real time
💻 Built-in "Developer IDE" Panel — A styled, syntax-highlighted code viewer that showcases the project's own logic directly in the UI
🎨 Premium Glassmorphism UI — Custom design system with gradient accents, blurred background blobs, and smooth animated counters



🛠️ Tech Stack

LayerTechnologyStructureHTML5StylingCSS3 (custom design system, CSS variables, glassmorphism)LogicVanilla JavaScript (ES6+)ChartsChart.js (via CDN)FontsPlus Jakarta Sans, Space Grotesk, JetBrains Mono (Google Fonts)DataStatic JS dataset derived from the UCI Online Retail dataset (RFM-processed)


No build tools, no backend, no dependencies to install — it's a pure client-side app that runs directly in the browser.




📂 Project Structure

Online-Retail/
├── index.html      # Main dashboard markup & layout
├── styles.css       # Design system, theming, and component styles
├── app.js           # Dashboard logic: charts, table, RFM simulator, IDE panel
├── data.js          # Precomputed RFM & summary data from the UCI dataset
└── README.md


🚀 Getting Started

No installation required.


Clone the repository


bash   git clone https://github.com/<your-username>/Online-Retail.git
   cd Online-Retail


Open it in your browser
Simply open index.html directly, or serve it locally:


bash   # Using Python
   python -m http.server 8000

   # Or using VS Code Live Server extension


Visit http://localhost:8000 and explore the dashboard.



📊 About the Dataset

The dashboard is powered by insights derived from the UCI Online Retail dataset, a real transactional dataset from a UK-based online retailer, covering all purchases made between December 2010 and December 2011.

Key stats reflected in the dashboard:


541,909 total transactions
4,372 unique active customers
£8.93M total revenue
91.7% of revenue from the United Kingdom


RFM scoring (Recency, Frequency, Monetary) was used to segment customers into 5 actionable groups, enabling targeted retention and marketing strategies for each.


🧠 What is RFM Analysis?

RFM is a customer segmentation technique that ranks customers based on three behavioral metrics:


Recency — How recently did the customer make a purchase?
Frequency — How often do they purchase?
Monetary — How much do they spend?


Combining these scores allows businesses to identify high-value customers, spot early churn signals, and design targeted retention campaigns instead of one-size-fits-all marketing.


🗺️ Roadmap


 Connect to a live backend/API for real-time data refresh
 Export customer segments as CSV/PDF reports
 Add cohort retention analysis view
 Dark/Light theme toggle



👤 Author

Dhushyanth Challa (Sai)
Final-year B.Tech CSE | Aspiring Full-Stack / SDE
🔗 GitHub · LinkedIn


📄 License

This project is open source and available under the MIT Licens
