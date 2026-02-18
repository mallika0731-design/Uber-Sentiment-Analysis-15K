🚖 Uber Sentiment Analysis – 15K Reviews

Natural Language Processing | Sentiment Classification | Executive Analytics

📌 Project Overview

This project builds a complete end-to-end NLP sentiment analysis pipeline on 15,000 real Uber app reviews.

The objective was to:

Clean and preprocess raw user-generated text

Perform sentiment classification using NLP techniques

Validate results against Uber star ratings

Generate executive-level insights and export-ready analytics

This capstone demonstrates practical application of Natural Language Processing, text preprocessing, sentiment modeling, performance validation, and business insight extraction.

🧠 NLP & Machine Learning Pipeline

1️⃣ Text Preprocessing

Lowercasing & normalization

Removal of URLs, emojis, punctuation

Regex-based cleaning

Handling multilingual review text

Token-level cleanup for consistent sentiment scoring

2️⃣ Sentiment Classification Model

Implemented VADER (Valence Aware Dictionary & sEntiment Reasoner)

Generated compound sentiment scores (-1 to +1)

Custom threshold logic for:

Positive

Neutral

Negative classification

3️⃣ Model Validation

Compared predicted sentiment with Uber star ratings

Measured real-world performance accuracy

📊 Executive Summary (Actual Project Results)

Dataset Size: 15,000 Uber app reviews
Processing Time: 29 seconds
Accuracy vs Star Ratings: 67.6%

Sentiment Distribution

Negative: 8,584 reviews (57.2%)

Positive: 5,083 reviews (33.9%)

Neutral: 1,333 reviews (8.9%)

⭐ Sentiment Breakdown by Star Rating
Star Rating	Total Reviews	% Negative
1 Star	9,948	70%
2 Stars	1,320	60%
3 Stars	899	51%
4 Stars	636	28%
5 Stars	2,197	9%

This demonstrates strong alignment between textual sentiment and user star ratings — validating model reliability.

💼 Business Insights Extracted

57.2% of Uber reviews are negative, indicating substantial dissatisfaction signals.

67.6% sentiment accuracy confirms meaningful alignment between NLP predictions and actual ratings.

8,351+ critical reviews require attention, providing a clear target segment for product improvement teams.

This project moves beyond classification — it converts raw reviews into actionable decision intelligence.

📁 Output Artifacts Generated

Uber_15K_Executive_Analysis.csv (15,000 rows)

Executive summary metrics

Sentiment distribution breakdown

Star-rating correlation analysis

Production-ready processed dataset


⚙️ Tech Stack

Python

pandas

numpy

vaderSentiment

langdetect

regex (re)

matplotlib

🏁 Capstone Status

✔ 15K reviews processed
✔ Production-grade pipeline
✔ Executive summary generated
✔ Business insights extracted

🎯 Why This Project Matters (Recruiter Perspective)

This project demonstrates:

Real-world NLP implementation

Large-scale text processing (15K records)

Model validation against ground truth

Data-to-decision workflow

Business insight extraction, not just modeling

It shows the ability to bridge machine learning with business intelligence, which is critical for applied data science roles.
