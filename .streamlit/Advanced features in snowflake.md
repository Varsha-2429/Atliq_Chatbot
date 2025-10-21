**Advanced features in snowflake:**



**A. Cortex AISQL**



**What it is:** Snowflake introduced AI functions like AI\_COMPLETE, AI\_FILTER, AI\_AGG, AI\_CLASSIFY, AI\_EMBED, AI\_SIMILARITY.



**Purpose:** Data analysis lo AI queries direct ga SQL lo cheyachu.



**Example:**



-- Table: HOTELS(name, description)

SELECT name, AI\_CLASSIFY(description, 'luxury, budget, family') AS category

FROM HOTELS;





**👉 Ee query hotel descriptions classify chestundi into luxury/budget/family automatically.**

