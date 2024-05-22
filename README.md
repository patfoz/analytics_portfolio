# Analytics reference

This is a reference for some of the data analytics work I have done and a useful reference for me for certain patterns or code that I re-use a bit and can copy from for other notebooks or analyses. 

**backstage_usage_analytics.ipynb**
<br>This is to begin to gauge the usage patterns of those using Spotify's Backstage internal developer portal to allow us to focus some of our roadmap investigations towards the areas of most interest to developers.

**devop_pipeline_analysis.ipynb**
<br>This analysis was to gauge how new templates we were buidling were being used and how the additional instrumentation that were built into these were able to determine the failure causes of pipelines. This data would eventually be productionised and persisted to Snowflake for processing via Power BI or Tableau. The data was fantastic to find issues we were unaware of and provide development teams insight into bottlenecks in their flow.

**infrastructure_sankey.ipynb**
<br>This was indulgent and really just used to learn how to structure data for Sankey diagrams. I came across a nice example by Microsoft that detailed their revenue in this way and thought it would be a nice representation to show how we are moving our infrastructure to be immutable and better maintained over time.

**ibm_spacex_ml_prediction.ipynb**
<br>This was the final part of the IBM Data Science Professional Certificate Capstone to find the best model to predict SpaceX landing outcomes.

