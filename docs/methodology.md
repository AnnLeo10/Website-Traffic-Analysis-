# Methodology

1. Loaded the event-level customer journey dataset.
2. Converted `Timestamp` to datetime and sorted events by `SessionID` and time.
3. Validated missing values and categorical fields.
4. Reconstructed each session's page journey from timestamp order.
5. Derived entry and exit pages.
6. Aggregated event records into one row per session.
7. Derived session duration, pages per session, bounce status and conversion status.
8. Calculated traffic, engagement, acquisition and conversion metrics.
9. Created visualizations for traffic trends, page views, sources, funnel progression, entry/exit behavior and device performance.
10. Translated analytical patterns into website optimization recommendations.

## Metric Definitions
- Page Views: number of event records associated with a page type.
- Sessions: unique `SessionID` values.
- Users: unique `UserID` values.
- Bounce Rate: percentage of sessions containing exactly one recorded event.
- Conversion Rate: percentage of sessions where `Purchased = 1`.
- Session Duration: difference between last and first timestamp within a session.
- Pages per Session: number of recorded page events in a session.
- Cart Abandonment: percentage of cart-reaching sessions that did not purchase.
- Checkout Abandonment: percentage of checkout-reaching sessions that did not purchase.

