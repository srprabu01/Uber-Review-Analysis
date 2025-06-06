
# Uber Review Insights

A Power BI dashboard project that analyzes Uber app user reviews collected between **November and December 2024**. This project explores customer sentiment, rating trends, review length patterns, and app version performance to uncover key insights into user experience and satisfaction.

---

## Project Overview

This project aims to provide a comprehensive view of Uber's customer feedback using visual analytics. By analyzing user-submitted reviews and metadata, we can:

- Understand sentiment distribution (Positive, Neutral, Negative)
- Track rating trends over time
- Explore review length as a proxy for feedback richness
- Identify differences across app versions

---

## Dashboard Features

- **Sentiment Analysis**: Visualized breakdown of positive, neutral, and negative reviews.
- **Rating Trends**: Line graph showing rating volume over time.
- **Review Length Trends**: Analysis of how review verbosity changes across dates and sentiment.
- **App Version Filters**: Selectable filters to isolate insights by app version.
- **Date Filtering**: Analyze reviews within a custom date range.
- **Interactive Elements**: Clickable visuals and filters for dynamic exploration.

---

## Tools Used

| Tool            | Purpose                            |
|----------------|-------------------------------------|
| **Power BI**    | Data visualization and dashboard creation |
| **Python (optional)** | Preprocessing reviews for sentiment classification |
| **Excel/CSV**   | Raw data storage and filtering      |

---

## Sample Visuals

- Sum of Ratings by Day
- Review Length Trends by Sentiment
- Donut chart for sentiment proportions
- App version-specific analysis

---

## Project Structure

```
├── data/
│   └── uber_reviews_nov_dec_2024.csv
├── dashboard/
│   └── Uber_Review_Insights.pbix
├── images/
│   └── dashboard_preview.jpg
├── README.md
```

---

## Key Insights (Nov–Dec 2024)

- **67.78%** of reviews were **positive**, indicating strong user satisfaction.
- **Negative sentiment** reviews showed higher average review lengths, suggesting detailed complaints.
- Review and rating spikes aligned with early December, possibly due to promotions or app updates.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/uber-review-insights.git
   ```
2. Open the `.pbix` file using Power BI Desktop.
3. Use filters (date, sentiment, rating, app version) to interact with the visuals.

---

## Feedback or Contribution

Feel free to open issues or submit pull requests for suggestions, improvements, or adding advanced analytics features (e.g., NLP, geospatial review mapping).

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
