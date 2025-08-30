# MongoDB-Analysis-Project
Analyzed the MongoDB sample_mflix dataset using MQL, writing 34 queries from basic lookups to advanced aggregations and geospatial queries, with results stored programmatically and visualized using Python (pymongo, geopandas, matplotlib).


**This project involved performing both basic and advanced analysis of the sample_mflix database using MongoDB Query Language (MQL). I set up a MongoDB instance via Docker on a Google Cloud VM, connected it to Jupyter with pymongo, and wrote queries to explore and analyze the dataset.**

**Key highlights:**

**Environment setup:** Configured MongoDB in Docker; used Jupyter, pymongo, pandas, geopandas, and matplotlib for querying and visualization.

**Database work:** Loaded and structured the sample_mflix dataset into MongoDB, working with collections like movies, users, and comments.

**Querying & analysis:**

Implemented 34 queries ranging from simple lookups (e.g., movies by Christopher Nolan, movies after 2000) to advanced aggregations (e.g., top directors, average ratings by genre, most active users).

Designed queries using operators such as $match, $group, $lookup, $addToSet, and $cond.

Stored query results programmatically as .pkl files for reproducibility.

**GeoJSON visualization:** Used spatial queries to map theaters across Wisconsin and Madison. Created visualizations showing theater proximity to landmarks (e.g., UW–Madison, Peninsula State Park).


**Skills practiced:**
MongoDB, NoSQL querying (MQL), aggregation pipelines, geospatial queries, data visualization, Docker, Python (pymongo, geopandas, matplotlib).
