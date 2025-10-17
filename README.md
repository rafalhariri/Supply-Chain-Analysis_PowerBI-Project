# Supply-Chain-Analysis_PowerBI-Project

 As the main data analyst for Just In Time, we will help solve key shipment and inventory management challenges, analyze supply chain inefficiencies, and create insightful dashboards to inform business stakeholders about potential problems and propose structural business improvements.
 
** Data Cleaning and Transformation**
After carefully investigating the data available; fulfilment, orders and shipment and inventory, some data issues were discovered and this is how they were addressed;

- Negative Shipment Time: Removed records of these transactions.
- Orders taking too long to ship: Given the shipment modes and reorder fulfilment times, it is highly unlikely that orders took more than 14 days to ship. Orders that took more than 14 days to ship were filtered.
- Correction of Country Names: Some country's names had special characters and these were corrected to ensure correct names.
- Discreptancecs between Inventory and Order records: Some sales were made on products that weren't recorded in the inventory. Assumption is made that this is an error in data compilation process.
