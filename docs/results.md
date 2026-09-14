# Results and insights

The [rendered report](index.html) contains the original tables, charts, and
analysis narrative. The [source notebook](../notebooks/FDS_Project_LearnerNotebook_FullCode.ipynb)
contains the calculations and business questions. The findings below are
limited to statements already present in those artifacts.

- The dataset contains 1,898 unique orders.
- Food preparation takes 20 minutes at minimum, 27.37 minutes on average,
  and 35 minutes at maximum.
- 736 orders, or 38.78%, have no rating.
- American cuisine is the most ordered (584 orders, 30.8%), followed by
  Japanese (470, 24.8%) and Italian (298, 15.7%).
- Shake Shack receives the most orders, followed by The Meatball Shop and Blue
  Ribbon Sushi.
- American cuisine is the most popular cuisine on weekends.
- Most orders cost less than $20; the notebook notes that half cost $14 or
  less.
- About 89.5% of orders are delivered within 60 minutes of order placement;
  the notebook separately reports that 10.54% take more than 60 minutes.
- Weekend mean delivery time is about 5–6 minutes longer than weekday mean
  delivery time.
- The notebook's illustrative revenue calculation reports $2,477 from orders
  below $20 and $3,688 from orders above $20 under its stated commission
  rules.

These values are transcribed from the supplied educational artifacts and were
not independently recomputed in this repository. They should not be treated
as production performance metrics.
