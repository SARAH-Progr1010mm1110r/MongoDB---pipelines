# MongoDB---pipelines
### **Connect to a MongoDB cluster, create MongoDB pipelines, query, export pipelines, create views, create dashboards**

# **Tasks:**
  1. In MongoDB Compass connect to cluster in MongoDB Atlas

  2. Upload the soccer_stats.csv dataset to MongoDB Compass (make sure to specify correct datatypes for each field)

  3. Create 6 pipelines for the soccer_stats data and save them to collections. It is required to use all of the aggregation operators: $match, $project, $group, $limit, $sort; some of the comparison operators ($gt, $lt, $gte, $lte, $ne, $eq), some of the logic operators ($and, $not, $nor, $or)

     * Query 10 top players by ranking;

     * List the players who were “Man of the match” more than 5 times;

     * Retrieve 20 youngest players, who scored 7 or more goals;

     * Retrieve how many yellow cards forwards received per team;

      * Count the number of goals by position per team;

  4. Export pipelines to separate files

  5. Create a view for each pipeline

  6. In MongoDB Atlas switch to the Charts tab. Go to Data Sources and add data source by clicking the “add data source” button. Choose your views from the dropdown.

  7. Create a dashboard based on your created views/pipelines. Graphs should represent the data from queries from step #3

  8. There will be 6 graphs in total, one per view/pipeline (each graph should have labels and titles). Create different types of graphs.
