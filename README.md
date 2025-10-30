# Uber_Cab_Analytics

This repository contains a Power BI dashboard built to analyze ride-hailing performance patterns across booking behavior, cancellation reasons, payment preferences, customer feedback, and fleet categories.

The analysis supports operational decisions related to demand concentration, route planning, cancellation mitigation, and experience improvement for riders and drivers.

---

## Key Objectives
- Track completed and cancelled bookings across time periods
- Evaluate revenue contribution and payment channel usage
- Monitor rider distance behavior and high-distance customers
- Compare performance across vehicle types (Auto, Bike, Sedan, XL, Mini)
- Review customer and driver ratings
- Analyze monthly and quarterly patterns

---

## Main Insights
- Evening hours show approximately 27% higher ride activity than morning hours
- UPI and wallet transactions represent strong payment adoption
- Core pickup clusters reflect high-density urban mobility zones
- Recurring cancellation themes involve route concerns, plan changes, and capacity issues
- Sedan and Mini categories demonstrate consistent booking patterns

---

## Technology Stack
| Component | Tool |
|---|---|
BI Platform | Power BI Desktop  
Data Shaping | Power Query  
Data Logic | DAX  
Data Storage | CSV source file  
Processing Support | SQL for cleansing and transformations  

---

## Dashboard Workflow
1. Import dataset into Power BI
2. Use Power Query to clean and format fields
3. Build calculations and KPIs with DAX
4. Create interactive pages for:
   - Overview
   - Distance
   - Customer
   - Vehicle category insights
5. Add navigation buttons, filters, and visuals
