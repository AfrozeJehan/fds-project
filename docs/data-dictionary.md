# Data dictionary

The definitions below are based on columns present in the local
`foodhub_order.csv` and the supplied notebook. The CSV is not tracked in this
repository.

| Column | Meaning | Role / notes |
| --- | --- | --- |
| `order_id` | Unique order identifier | Identifier |
| `customer_id` | Identifier of the customer who placed the order | Identifier |
| `restaurant_name` | Restaurant receiving the order | Categorical dimension |
| `cuisine_type` | Cuisine selected for the order | Categorical dimension |
| `cost_of_the_order` | Order cost in dollars | Numeric measure |
| `day_of_the_week` | `Weekday` or `Weekend` order classification | Categorical dimension |
| `rating` | Customer rating out of 5, or `Not given` | Rating measure; missing response is represented as text |
| `food_preparation_time` | Minutes from restaurant confirmation to rider pickup | Numeric duration |
| `delivery_time` | Minutes from pickup to customer delivery | Numeric duration |

