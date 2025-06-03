# Music Store Data Analysis

**Project Overview** 
This Project explores data from a digital music store to derive business insights using SQL. The dataset mimics a real-world scenario with customers, invoices, employees, tracks, artists, albums, and genres. The goal is to perform analysis across different complexity levels—basic, moderate, and advanced—to support strategic decision-making in sales, marketing, and customer management.

**🎯 Objective**
To analyze sales and customer data to identify top-performing entities (e.g., best customer, most profitable city).
To segment and understand customer preferences based on music genre.
To identify business opportunities such as top artists, popular genres by country, and high-spending customers.
To showcase SQL querying skills across various difficulty levels using real-world analytical scenarios.

**Dataset Description**
The dataset includes multiple interconnected tables:

Customer – details of customers including location and contact.
Invoice and Invoice_Line – sales transactions with details on items purchased.
Track, Album, Artist, Genre – metadata about music content.
Employee – employee roles and hierarchy.
This relational schema enables multidimensional insights via JOIN operations and aggregations.

![image](https://github.com/user-attachments/assets/f82840f5-e8cd-46aa-a043-8be48919d473)

**🛠 Tools & Libraries Used**
Postgre SQL
PgAdmin4

**Analysis Report**

The analysis was structured into three levels:

***Level A***

Identified the senior-most employee by job title.
Found countries with the most invoices (likely strong market presence).
Listed top 3 invoice totals, revealing highest individual purchases.
Determined the best customer city based on total revenue.
Identified the top spending customer.

***Level B***

Extracted details of Rock music listeners.
Ranked the top 10 artists with the most Rock tracks.
Listed tracks longer than average length, useful for understanding track trends.

***Level C***

Analyzed customer spending by artist, pinpointing revenue-driving fans.
Found the most popular genre per country using purchase frequency.
Determined the top-spending customer in each country using window functions.

**Key Takeaways**

***Top Revenue Source:*** A single city and a handful of customers significantly impact revenue.
***Genre Preference:*** Rock is a dominant genre with widespread listenership and artist participation.
***Artist Engagement:*** A small set of artists are responsible for a large proportion of tracks.
***Customer Segmentation:*** High-value customers and genre-based segmentation can guide personalized marketing.
***Global Trends:*** Spending patterns and genre preferences vary significantly across countries.

**Conclusion**

The Music Store Data Project demonstrates the power of SQL for business intelligence in the entertainment industry. By identifying key customer behaviors, revenue trends, and artist performance, the project offers actionable insights that can guide marketing strategies, product offerings, and event planning.

Whether you're launching a promotional event or seeking to increase customer retention, these insights provide a solid foundation for data-driven decisions.

**Recommendations**

***1. Focus Marketing Efforts on High-Revenue Cities***

Insight: One city generated the most revenue.
Action: Launch local events (e.g., music festivals, exclusive releases) in that city to reinforce brand loyalty and maximize ROI.

***2. Prioritize High-Spending Customers***

Insight: A small number of customers contribute disproportionately to revenue.
Action: Implement a loyalty or VIP program to retain top spenders with benefits like early access, discounts, or personalized playlists.

***3. Capitalize on Rock Genre Popularity***

Insight: Rock is the most consumed genre globally.
Action: Promote Rock music through curated playlists, social media content, and featured artist collaborations. Consider bundling Rock albums or tracks in promotions.

***4. Invest in Top Artists***

Insight: A few artists produce a large volume of popular content.
Action: Strengthen relationships with top-performing artists through promotional partnerships, exclusive content deals, or featured placement on the platform.

***5. Personalize Offerings by Country***

Insight: Popular genres vary by country.
Action: Use country-level genre preferences to tailor marketing campaigns, regional recommendations, and localized playlists to increase user engagement.

***6. Improve Long Track Promotion***

Insight: Tracks longer than average were identified.
Action: Highlight these in special playlists (e.g., “Epic Songs” or “Extended Mixes”), as they may appeal to niche audiences and increase session time.

***7. Expand into Underperforming Countries***

Insight: Some countries have lower purchase volumes.
Action: Run targeted campaigns or offer discounts to boost acquisition and sales in underpenetrated markets.

***8. Optimize Customer Communication***

Insight: Email and customer data were used in queries.
Action: Leverage email marketing to recommend genres/artists based on past purchases or listening behavior.

**🤝 Contributing**

Feel free to fork this project and contribute. For suggestions or improvements, please open an issue or submit a pull request.

**📬 Contact**

Author: Aayushi Gupta

LinkedIn: [https://www.linkedin.com/in/aayushi-gupta-8757371a9/]

GitHub: [https://github.com/Aayushigupta357/Music-Store-Data-Analysis]
