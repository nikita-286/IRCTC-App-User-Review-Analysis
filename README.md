### IRCTC App User Review Analysis

I performed an analysis of IRCTC app reviews to identify recurring user issues such as payment failures, Tatkal booking delays, vague error messages, login problems and app crashes. Extracted insights using Python for data cleaning, EDA and n-gram analysis to pinpoint common complaints and deliver actionable recommendations for improving user experience.

### Dataset
The dataset was collected via **web scraping** from the IRCTC app and contains the following columns:

| Column Name   | Data Type | Description |
|---------------|-----------|------------|
| `Review ID`    | object    | Unique identifier for each review |
| `Review Text`  | object    | Textual feedback from users |
| `Rating`       | int64     | User rating (e.g., 1–5 stars) |
| `Date`         | object    | Date of the review |
