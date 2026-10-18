MIS 790 MSIS Synthetic Analysis Dataset
Rows: Orders=3,000; International_Leg=2330; Domestic_Leg=3,000; Event_Calendar=10; Node_Lookup=27.
All timestamps are UTC ISO-8601. Primary/foreign keys follow the exam appendix.
Use pandas/SQL/R/Excel as desired. The dataset intentionally contains normal variation, correlated disruptions, tariff windows, and modal differences so that students must compute results rather than repeat definitions.
Recommended execution: join Orders to both legs; validate referential integrity; calculate landed cost, delays, SLA compliance, disruption rates, route/modal comparisons, and sensitivity/scenario results.
