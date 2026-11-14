# snapchat-streak-notification-ab-test
Should Snapchat Ship a Streak-Reminder Notification? An End-to-End Product Analytics Case Study

# Should Snapchat Ship a Streak-Reminder Notification?

An end-to-end product analytics case study: metrics design, A/B test analysis, variance reduction, guardrails, and a ship/no-ship recommendation.

**Note:** All data is synthetic.

## Notebooks
- `notebooks/01_streak_notification_ab_test.ipynb`
## Status
In Progress
## Key findings so far
- With 10,000 users, the A/B test found no significant difference
  (lift -0.04%, p = 0.984), even though a true +2% lift exists.
- This is a false negative: high variation in snap counts means the test
  was underpowered at this sample size.

  ## Tools
Python, pandas, NumPy, DuckDB, Google Colab
