# Track-the-top-editors-of-film-Wikipedia-pages-for-Walt-Disney

Wikipedia is one of the most important sources that our audience uses to learn about films -- the Wikipedia pages for films are some of the more commonly viewed and edited pages on Wikipedia.

Since Covid-19, Disney+ streaming subscriptions have grown rapidly. There are so many great movies, like Star Wars: The Force Awakens, Guardians of the Galaxy, The Avengers, Black Panther, and many more. At this time, the quality of the content on the Disney movie page of Wikipedia is extremely important. I’ll use tools and methods to track the top editors of film, and Wikipedia pages for Walt Disney.

The quality of the content on the Disney movie page of Wikipedia is extremely important. I would like to understand who the "top" Wikipedia film contributors are and build a dashboard around this for easy access by Data Analysis. Specifically, I want to know which users are most active in editing the Wikipedia pages for films. But let's take it a little further, I want to track the top editors for film pages and the Wikipedia pages that frequently link out to specific film pages as well (for example, Star Wars links to several film pages).

# Elaboration/Implementtion of concept

To complete the project, I'll use Databricks which is a Unified Data Analytics Platform - One cloud platform for massive-scale data engineering and collaborative data science. If you'd like an overview of how Databricks notebooks work, please see this documentation: https://docs.databricks.com/user-guide/notebooks/index.html
Wikipedia Referral Links There is clickstream referral data located at https://meta.wikimedia.org/wiki/Research:Wikipedia_clickstream

Wikipedia Article Data This data contains information on when a given editor makes an edit to a specific page. It is located at https://xtools.wmflabs.org/articleinfo/en.wikipedia.org/Star_Wars:_The_Force_Awakens revisionUsername is the editor name, title is the plain text title of the page, and revisionTimestamp is the timestamp of the edit.

Disney Wikipedia Pages There is a list of all Disney Wikipedia pages, Disney along with pageviews.: https://en.wikipedia.org/wiki/Wikipedia:WikiProject_Disney/Popular_pages 
