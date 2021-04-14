<img src="https://user-images.githubusercontent.com/7569632/42744038-a10351c8-88c9-11e8-858b-3a1e832dba4d.jpeg" alt="RRE" width="150px"/>

# RRE Walkthrough Demo Repository

The repository contains a sample RRE-enabled project used for the demo at the Search Relevance Training course.
It contains Solr configurations we devised to fully showcase RRE capability, using an ecommerce dataset from icecat-products-150k-20200809.

TO RUN:
UI for Evaluation Results
java -jar rre-server-1.1.jar

Data Dirs for the tmp Solr instances
mkdir /tmp/data1
mkdir /tmp/data2
mkdir /tmp/data3
mkdir /tmp/data4

Evaluate
mvn rre:evaluate

Visualize
mvn rre-report:report
