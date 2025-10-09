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
you can interact with dashboard from here:[https://app.powerbi.com/groups/me/reports/ff735602-6ec8-4755-aed4-27c0db086867/0a5cfd9651f9ff7dd719?experience=power-bi&bookmarkGuid=1d831e0ca885a603e57e](https://app.powerbi.com/groups/me/reports/ff735602-6ec8-4755-aed4-27c0db086867/0a5cfd9651f9ff7dd719?experience=power-bi)
<img width="1741" height="816" alt="2" src="https://github.com/user-attachments/assets/0af939ad-a08e-4a7d-a49e-922728b022d8" />
<img width="1740" height="817" alt="3" src="https://github.com/user-attachments/assets/b09b2ee7-0319-4843-b3d6-4a297958a361" />
<img width="1736" height="817" alt="4" src="https://github.com/user-attachments/assets/70725a64-fdc9-4ecb-a6b6-c5114958e823" />
<img width="1466" height="822" alt="5" src="https://github.com/user-attachments/assets/7eb99546-60e4-41bd-a82a-d707cb7e3c46" />

