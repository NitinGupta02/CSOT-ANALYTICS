# Week 1 Problem Statement: Quantifying the Bleed

## The Context
SwiftCart operates a network of 50 dark stores focused on delivering daily essentials in under 15 minutes. Because the business relies on tight margins and ultra-fast commerce, efficiency is critical.

## The Core Problem
Currently, store managers rely on manual inventory guesswork to stock daily goods. This manual approach is causing the company to lose margin at both ends of the supply chain through two costly errors:
* **Mistake A (Overstocking):** Buying too much to be safe results in spoiled food, generating a 12% perishable wastage rate across the network.
* **Mistake B (Understocking):** Buying too little to save money results in an 8% stockout rate during peak hours, causing high-value customers to switch to competitors.

## Your Mission
Perform an Exploratory Data Analysis (EDA) on SwiftCart’s current operations dataset. Your objective is to move beyond the percentages and quantify the exact annualized financial losses caused by this manual procurement. Calculate the raw cost of the wasted perishable goods and the estimated revenue lost from peak-hour stockouts. Your final deliverable should establish the baseline "bleed," proving mathematically why human managers cannot accurately predict demand.

---

## The Dataset
Since analyzing 50 stores over a full year requires a robust dataset, I have provided a sample CSV snippet (csv file) you can use immediately to understand the schema.

### The Data Dictionary (What the columns mean)
* **Date:** The specific date of operations.
* **Store_ID:** Identifies which of the 50 dark stores the data belongs to (e.g., ST-001).
* **SKU_Category:** The type of product (Produce, Dairy, Bakery, Pantry, Snacks). Perishables will have higher wastage.
* **Unit_Cost:** What SwiftCart pays for the item.
* **Retail_Price:** What the customer pays for the item.
* **Units_Ordered:** The number of items the manager guessed they needed.
* **Units_Sold:** The actual number of items purchased by customers.
* **Units_Spoiled:** Items that expired and were thrown away (Mistake A).
* **Stockout_Flag:** Binary indicator (1 = ran out of stock, 0 = stayed in stock) (Mistake B).
* **Peak_Hour_Stockout:** Binary indicator showing if the stockout happened during high-demand hours.
* **Est_Lost_Sales:** The estimated number of units customers would have bought if the item wasn't sold out.