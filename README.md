# Zomato Data Analysis

This project explores customer behavior, preferences, and restaurant performance using a dataset from Zomato. The goal is to draw insights on restaurant types, ratings, votes, and the impact of online ordering using Python libraries such as Pandas, Matplotlib, and Seaborn.

## 📁 Dataset

The dataset is a CSV file named `Zomato data.csv` that contains information about:
- Restaurant name
- Type of service (online/offline)
- Ratings
- Number of votes
- Cost for two
- Restaurant category (listed_in(type))

## 🧹 Data Cleaning

- **Ratings Column (`rate`)**: Converted to float from strings like "4.1/5".
- Handled missing or non-numeric values appropriately.

## 📊 Analysis Performed

1. **Restaurant Types**  
   - Most customers prefer **dining** restaurants over others.

2. **Votes Received by Restaurant Type**  
   - Dining restaurants have received the **maximum number of votes**.

3. **Ratings Distribution**  
   - Majority of restaurants received ratings between **3.5 and 4.0**.

4. **Cost for Two People**  
   - Most common average cost for two people is **₹300**.

5. **Rating Comparison: Online vs Offline Orders**  
   - **Online orders** receive slightly higher ratings on average compared to offline.

6. **Restaurant Type vs Online Ordering**  
   - **Dining** restaurants are more common in offline orders.
   - **Cafes** are preferred for **online** orders.

## 📈 Visualizations

Used `matplotlib` and `seaborn` for:
- Countplots
- Line plots
- Histograms
- Boxplots
- Heatmaps

## 🛠️ Libraries Used

- pandas
- numpy
- matplotlib
- seaborn

## 📌 Conclusion

This analysis helps understand:
- Customer preferences across restaurant types.
- Influence of online ordering on ratings.
- Spending behavior for two people.
- Performance of different restaurant types based on votes.

## 💡 Future Scope

- Sentiment analysis on reviews.
- Time series analysis of order trends.
- Geo-mapping based on location data.
