---
title: "UnwRappler: Revealing Rappler's Underlying Focus"
date: 2019-06-23 # should be a year-month-date format
tags: [machine learning, data science, data mining, data wranggling, clustering]
image: "/images/07_unwrap_dmw.JPG"
header:
  image: "/images/07_unwrap_dmw.JPG"
excerpt: "Identifying Underlying Themes in Rappler News Articles using Unsupervised Clustering Techniques"
mathjax: "true"
---
## Executive Summary 
Rappler, one of the leading online news publishers in the Philippines, seeks to inspire community engagement and create action for social change through citizen journalism. However, it has recently been under scrutiny by the Philippine government for “twisted” reporting. 

This study aims to uncover the underlying themes of Rappler news articles via unsupervised clustering techniques and see if there is an inherent concentration of news in a specific theme. A total of 11,079 articles were extracted from Rappler’s national news section published from January 2018 to May 2019. Features were extracted from the articles using a term frequency-inverse document frequency (TF-IDF) vectorizer and dimensions were reduced by implementing Latent Semantic Analysis (LSA). Lastly, unsupervised clustering via k-means algorithm was applied to group the articles and internal validation metrics were utilized to determine the optimal number of clusters. 

Ten clusters were uncovered, with Philippine President Rodrigo Duterte as the dominant cluster. The remaining themes touch on different branches of government, police and weather updates, and trending national issues. The insights gained from this research can aid Rappler in balancing its reporting by lessening bias towards specific topics.
##### Authors: Carmelita Esclanda, George Allan Esleta, Elmer Robles, Sandro Luis Silva 
<br>
#### Note: For the technical paper (PDF), data and the code used in this project, you may send me an [email](cgesclanda@gmail.com) or you can also drop your message via [LinkedIn](https://www.linkedin.com/in/carmelita-esclanda-566b2946/).
<br>

<img src="{{ site.url }}{{ site.baseurl }}/images/07_unwrap_dmw_poster.jpg" alt="unwrappling themes">

