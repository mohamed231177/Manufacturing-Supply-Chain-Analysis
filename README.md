# Manufacturing-Supply-Chain-Analysis
This project focuses on analyzing manufacturing quality and vendor performance by tracking product defects and operational downtime. The dashboard is designed to provide actionable insights into plant efficiency, material reliability, and vendor accountability to minimize production losses.

## dataset used
- <a href=  "https://github.com/mohamed231177/Manufacturing-Supply-Chain-Analysis/blob/main/Supplier%20Quality%20Analysis-dataset.xlsx"> dataset</a>

##  Questions (KPIs)
- What is the total volume of defects identified and the resulting operational downtime in minutes?

- Which manufacturing plants are experiencing the highest frequency of defects?

- How do different material categories (e.g., Packaging, Mechanicals, Electrical) compare in terms of defect quantity?

- What are the primary defect types (Impact, No Impact, Rejected) and their distribution across the supply chain?

- Which vendors are responsible for the highest defect rates and downtime impact?

- What is the average downtime incurred per defect, and how does it trend over time?

- How does plant performance contribute to the overall defect percentage?
- dashboard interaction <a href=  "https://github.com/mohamed231177/Manufacturing-Supply-Chain-Analysis/blob/main/page%201.png">view dahboard </a>

## process 
- Data Cleaning & ETL: Prepared and cleaned the manufacturing dataset, focusing on defect counts, downtime minutes, and category standardization.

- Star Schema Modeling: Established a highly optimized Star Schema to connect operational data:

- Fact Table: Defect Report (containing core metrics like Defect Qty and Downtime min).

- Dimension Tables: Defect Type, Category, Material Type, Plant, and Vendor.

- Data Modeling & Relationships: Implemented one-to-many relationships between dimension tables and the central fact table to enable seamless cross-filtering.

## dashboard 
<img width="1771" height="736" alt="page 1" src="https://github.com/user-attachments/assets/f2548bae-99c5-415a-97b9-d3cfb38d72dd" />
<img width="1298" height="727" alt="page 2" src="https://github.com/user-attachments/assets/7c23d32a-5487-49f5-817f-84d6b9760284" />
<img width="1306" height="725" alt="page 3" src="https://github.com/user-attachments/assets/a7d354cd-828e-4e05-9227-101c217a65e0" />
<img width="1342" height="731" alt="page 4" src="https://github.com/user-attachments/assets/e7e0dfc1-c80d-43da-8b07-ca1ba24e7fac" />
<img width="1760" height="723" alt="page 5" src="https://github.com/user-attachments/assets/bb370a9b-063f-4b7f-989d-5e450478e620" />

## Final Conclusion 
- Operational Efficiency: The analysis provides a clear roadmap for reducing downtime by identifying the specific plants and categories where defect density is highest.

- Vendor Accountability: By tracking vendor-specific defect percentages, the organization can make data-driven decisions regarding supplier contracts and quality requirements.

- Material Quality Control: The breakdown by material type highlights which components require stricter quality inspections during the procurement phase.






