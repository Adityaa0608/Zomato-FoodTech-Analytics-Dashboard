# Zomato-FoodTech-Analytics-Dashboard
🍕 Zomato Food-Tech Insights: Operational & User Analysis Dashboard
An interactive, multi-page Power BI application designed to explore Zomato's vast operational data—focusing on sales performance, user demographics, customer churn, and regional city-wise growth.
🚀 Project Overview
The Zomato Food-Tech Insights Dashboard is a high-fidelity analytical tool built to help business stakeholders monitor and optimize a food-delivery network spanning over 150,000 cities and 100,000 users. By bridging the gap between complex transactional data and UI/UX design, this dashboard identifies top-performing regions, analyzes user retention (Gained vs. Lost), and tracks cuisine preferences to drive strategic decision-making.
📂 Tech Stack
The dashboard was built using a "Design-First" approach with the following technologies:
📊 Power BI Desktop – Main platform for report authoring and interactive visualization.
📂 Power Query – Used for ETL (Extract, Transform, Load) to clean and shape the 150K+ row dataset.
🧠 DAX (Data Analysis Expressions) – Implemented for advanced measures, including the dynamic Amount vs. Quantity toggle and customer retention logic.
🎨 Figma – Used to design the custom high-fidelity UI backgrounds, ensuring an app-like user experience.
📝 Data Modeling – Established a star schema to enable seamless cross-filtering between City, User, and Order tables.
📁 Data Source
The analysis is based on a comprehensive dataset representing Zomato's digital footprint:
Scale: Data covering 150,281 orders across 150,281 cities and 100,000 users.
Attributes: Includes sales amounts, quantities, user age, gender, restaurant ratings, and cuisine types (Veg/Non-Veg).
✨ Features & Highlights
📉 Business Problem
In a hyper-competitive food-tech market, stakeholders need to answer critical questions:
Which cities are generating high volume but low ratings?
Are we losing more customers than we are gaining in specific age groups?
How do sales patterns differ when looking at order count vs. total revenue?
Raw data makes these trends invisible; this dashboard makes them actionable.
🎯 Goal of the Dashboard
To deliver a "Command Center" visual tool that:
Tracks real-time growth across a massive geographical scale.
Analyzes User Churn (Lost vs. Gained) to optimize marketing spend.
Simplifies complex reporting through a designer-level interface.
🔍 Walkthrough of Key Visuals
Landing Page: A professional, brand-consistent entry point that establishes the Zomato visual identity.
Dynamic Overview (Toggle System): A custom-built feature allowing users to switch the entire dashboard view between Sales Amount and Order Quantity using a single click.
Cuisine Performance: Visual cards comparing Non-Veg, Veg, and Other sales categories along with their respective average ratings.
User Analysis (Churn Logic): A dedicated page tracking the "Gain" and "Loss" of customers by gender, paired with an age distribution bar chart to identify the target "Power User" demographic (Age 20-30).
City Performance Map: A geospatial visualization showing sales intensity across the globe, supported by a detailed ranking list of Top 10 to Top 50 cities.
💡 Business Impact & Insights
Retention Strategy: Marketing teams can use the "Lost Customer" visual to target specific demographics (e.g., Males age 25) with specialized discount codes.
Operational Optimization: Identify cities with high sales but low ratings (e.g., Bikaner) to investigate restaurant partner quality.
Product Focus: Discovered that Veg Sales (156K) are outperforming Non-Veg (140K), suggesting a shift toward plant-based menu optimization
