## ⚙️ Project Requirements  
The project was built based on a **Business & Functional Requirement Document (BRD/FRD)**:  
- Assemble sales reports into a single fact table.  
- Ensure dynamic loading of yearly sales data (resilient ETL process).  
- Data cleaning and transformation for Geography, Product IDs, and Date formatting.  
- Build a star-schema data model with relationships.  
- Create DAX measures to calculate business KPIs.  

---

## 🛠️ Data Sources  
- **Sales Data** (CSV/Excel, by year)  
- **Product Data** (CSV/Database)  
- **Geography, Categories, Subcategories, SalesRep** (Excel files)  

---

## 🔑 Key Features  

### 🔹 Data Modeling & Transformation  
- Split *Country* and *City* from the `Location` field.  
- Created **GeoKey** for mapping and joining tables.  
- Standardized IDs using reusable Power Query functions.  
- Built a robust **Date Table** for time intelligence.  

### 🔹 DAX Measures  
- **Total Revenue** = Units × Retail Price  
- **Total Cost** = Units × Standard Cost  
- **Gross Profit** = Revenue – Cost  
- **Gross Profit MoM Growth %**  
- **Revenue QoQ Growth %** (QBR analysis)  
- **Average Sales per Day**  

### 🔹 Dashboard Visuals & Interactivity  
- KPI Cards: Revenue, Cost, Gross Profit, Growth %, Avg Sales/Day.  
- **Revenue by Month** (trend Jan–Dec).  
- **Top/Bottom 5 Products by Revenue & Cost**.  
- **Revenue by Sales Rep** and **by Category**.  
- **Geographical Map** for sales by city & country.  
- **Bookmarks**: Predefined dashboard views (e.g., Summary vs. Detailed).  
- **Drillthrough**: Right-click navigation for deep dives at Product, Category, or Sales Rep level.  
- **Dropdown Slicers**: For tracking performance by **Year, Quarter, Category, Subcategory, or Geography**.  

---

## 📈 Key Insights  
- **Total Revenue:** $126M  
- **Total Cost:** $39M  
- **Gross Profit:** $87M  
- **Avg Sales per Day:** $111K  
- **Top Products:** Quad, Carlota, Magnum  
- **Revenue split:** Special (64%) vs General (36%)  

---

## 🛠️ Tools & Technologies  
- **Power BI Desktop** (Data Modeling, DAX, Bookmarks, Drillthrough, Dropdown Slicers, Visuals)  
- **Power Query (M)** (Data Cleaning & Transformation)  
- **Excel / CSV / Database** (Data Sources)  

---

## 🚀 Deliverables  
- Interactive **Power BI Dashboard** with slicers, bookmarks & drillthrough navigation.  
- Automated yearly data refresh mechanism.  
- KPIs & insights tailored for **Quarterly Business Reviews (QBRs)**.  

---

## 📸 Dashboard Preview
<img width="1399" height="671" alt="1" src="https://github.com/user-attachments/assets/ad3b0c0d-84ef-4eef-a511-ee56b4db9a95" />
<img width="1396" height="663" alt="2" src="https://github.com/user-attachments/assets/09c4896a-aa06-498f-a9cb-663db2b5dc89" />
<img width="1391" height="668" alt="3" src="https://github.com/user-attachments/assets/4488c28e-6550-4e3a-a7c0-fe70338549f3" />
