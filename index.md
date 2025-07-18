---
layout: none
title: Halaman Utama
---
<nav>
  <a href="#projects">Projects</a>
  <a href="#skills">Skills</a>
</nav>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');

  body {
    margin: 0;
    padding: 2rem;
    min-height: 100vh;
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(to right, #0f2027, #203a43, #2c5364); /* Moonlit Asteroid */
    color: #ffffff;
  }

  h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    font-weight: 600;
  }

  p {
    font-size: 1.2rem;
    font-weight: 400;
  }
</style>

<div style="display: flex; align-items: center; gap: 20px;">
  <div>
    <h2>Hi, I'm Khalila Izzatunnisa</h2>
    <p>
      A highly motivated final-year Statistics student with a strong interest in data analytics,
      eager to broaden hands-on experience and contribute to impactful data-driven projects.
    </p>
  </div>
    <img src="images/formal-photo.jpg" alt="Profile Photo"
       style="width: 200px; height: 200px; border-radius: 50%; object-fit: cover;">
</div>


<a href="https://www.linkedin.com/in/khalilaiztns/" target="_blank">
  <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn" style="width:20px; height:20px;">
</a>


<a href="mailto:khalilaizztnns@gmail.com">
  <img src="images/gmail.png" alt="Gmail" style="width:23px; height:20px;">
</a>


<section id="projects" style="padding: 60px 20px;">
  <h2>Projects</h2>
  
  <div style="border:1px solid #ccc; padding: 10px; border-radius: 5px;">
    <h4>Application of Association Rule for Optimizing Sales Strategies in the Bakery Business</h4>
    <p>Using sales data from a bakery store, association rule analysis is applied to identify purchasing patterns and relationships between products. This analysis aims to uncover insights into customer buying behavior, such as which items are frequently bought together, in order to inform and optimize marketing strategies and promotional offers.</p>
    <a href="https://github.com/khalilaizztnns/association-rule-bakery-data" target="_blank" style="text-decoration: none;">
      <button style="padding: 6px 12px; background: #f8f8f8; color: #000; border: 1px solid #ccc; border-radius: 4px; cursor: pointer; display: inline-flex; align-items: center; gap: 6px;">
        <span>View on</span>
        <img src="images/github-full.png" alt="GitHub Logo" width="50" height="20" style="background: transparent;">
      </button>
    </a>
  </div>

  <br>

  <div style="border:1px solid #ccc; padding: 10px; border-radius: 5px;">
    <h4>Designing a Database for Wellness Studio</h4>
    <p>Designed a database system for a wellness studio, focusing on modeling the relationships between key entities such as services, subscription packages, members, classes, instructors, transactions, and bookings. An Entity Relationship (ER) Diagram was constructed to represent the logical structure of the system and visualize how the entities are interconnected. The implementation was carried out using Structured Query Language (SQL) with MySQL.</p>
    <a href="https://github.com/khalilaizztnns/wellness-studio-database" target="_blank" style="text-decoration: none;">
      <button style="padding: 6px 12px; background: #f8f8f8; color: #000; border: 1px solid #ccc; border-radius: 4px; cursor: pointer; display: inline-flex; align-items: center; gap: 6px;">
        <span>View on</span>
        <img src="images/github-full.png" alt="GitHub Logo" width="55" height="22" style="background: transparent;">
      </button>
    </a>
    <a href="https://univindonesia-my.sharepoint.com/:x:/g/personal/khalila_izzatunnisa_office_ui_ac_id/EZFG5Y41hM5Pv_cSJAK5dhkBr75GrkxapbOCCUQQd9DfFg?e=f2iBlm" target="_blank" style="text-decoration: none;">
      <button style="padding: 6px 12px; background: #f8f8f8; color: #000; border: 1px solid #ccc; border-radius: 4px; cursor: pointer; display: inline-flex; align-items: center; gap: 6px;">
        <span>View on</span>
        <img src="images/excel-full.png" alt="Tableau Logo" width="40
      " height="" style="background: transparent;">
      </button>
    </a>
  </div>
  
  <br>

  <div style="border:1px solid #ccc; padding: 10px; border-radius: 5px;">
    <h4>Geospatial Analysis of Hospital Accessibility in DKI Jakarta</h4>
    <p>Using spatial data obtained from OpenStreetMap, a network analysis was conducted to evaluate hospital accessibility in the DKI Jakarta region. The analysis included network statistics, degree centrality, and the measurement of the shortest distance from each hospital to the nearest road network node. Degree centrality was utilized to identify key intersections or nodes that play a strategic role in urban connectivity, while distance analysis assessed the spatial proximity of hospitals to major transport links, providing insights into the ease of physical access to healthcare facilities across different areas of the city.</p>
    <a href="https://github.com/khalilaizztnns/geospatial-analysis-jkt-hospital-accessibility" target="_blank" style="text-decoration: none;">
      <button style="padding: 6px 12px; background: #f8f8f8; color: #000; border: 1px solid #ccc; border-radius: 4px; cursor: pointer; display: inline-flex; align-items: center; gap: 6px;">
        <span>View on</span>
        <img src="images/github-full.png" alt="GitHub Logo" width="55" height="22" style="background: transparent;">
      </button>
    </a>
  </div>
  
  <br>

  <div style="border:1px solid #ccc; padding: 10px; border-radius: 5px;">
    <h4>Gene Expression Analysis of Whole Blood in Pediatric Septic Shock Using Supervised and Unsupervised Learning Methods</h4>
    <p>Using whole blood gene expression data from children (age ≤10 years) within the first 24 hours of admission to the Pediatric Intensive Care Unit (PICU) due to septic shock, obtained from the Gene Expression Omnibus (GEO), a comprehensive analysis was conducted. This included differential gene expression analysis to identify significantly expressed genes between healthy controls and septic shock patients; supervised learning for classification between the two groups using Logistic Regression, K-Nearest Neighbors, and Support Vector Machine models; unsupervised learning through clustering using K-Means Clustering, Hierarchical Clustering, Gaussian Mixture Model, HDBSCAN, and OPTICS models to group genes into specific clusters and biclustering using Spectral Biclustering to simultaneously cluster both genes and samples based on expression data; and gene ontology (GO) enrichment analysis to explore the potential biological functions associated with genes linked to septic shock.</p>
    <a href="https://github.com/khalilaizztnns/septic-shock-gene-expression-analysis" target="_blank" style="text-decoration: none;">
      <button style="padding: 6px 12px; background: #f8f8f8; color: #000; border: 1px solid #ccc; border-radius: 4px; cursor: pointer; display: inline-flex; align-items: center; gap: 6px;">
        <span>View on</span>
        <img src="images/github-full.png" alt="GitHub Logo" width="55" height="22" style="background: transparent;">
      </button>
    </a>
  </div>

  <br>

  <div style="border:1px solid #ccc; padding: 10px; border-radius: 5px;">
    <h4>Topic-Level Sentiment Analysis of the 32% U.S. Import Tariff Policy on Indonesia Using a BERT-Based Approach</h4>
    <p>Using data scraped via the YouTube Data API v3 from the comment section of the video “Digebuk Tarif 32% Trump! Ekonomi Indonesia Bisa Jeblok?” uploaded by the Metro TV channel, topic-level sentiment analysis was conducted. BERTopic was applied for topic modeling to group comments into specific topics, and XLM-RoBERTa was used for zero-shot sentiment classification to categorize each comment as either positive or negative. The goal was to examine the sentiment distribution, positive and negative, within each identified topic.</p>
    <a href="https://github.com/khalilaizztnns/topic-modelling-and-sentiment-analysis-us-id-tariff" target="_blank" style="text-decoration: none;">
      <button style="padding: 6px 12px; background: #f8f8f8; color: #000; border: 1px solid #ccc; border-radius: 4px; cursor: pointer; display: inline-flex; align-items: center; gap: 6px;">
        <span>View on</span>
        <img src="images/github-full.png" alt="GitHub Logo" width="55" height="22" style="background: transparent;">
      </button>
    </a>
  </div>

  <br>

  <div style="border:1px solid #ccc; padding: 10px; border-radius: 5px;">
    <h4>Understanding e-Paylater Usage Through Demographic Segmentation and Psychometric Analysis</h4>
    <p>Using data obtained from Mendeley Data contains information on respondents’ demographic characteristics and survey responses regarding the use of e-Paylater services. The analysis involved exploring respondent profiles based on demographic characteristics by distinguishing between users and non-users of e-Paylater, conducting validity and reliability tests to assess whether the survey items were valid and the instrument reliable, and performing user segmentation through K-Modes Clustering based on demographic attributes.</p>
    <a href="https://github.com/khalilaizztnns/analysis-online-ibb-survey" target="_blank" style="text-decoration: none;">
      <button style="padding: 6px 12px; background: #f8f8f8; color: #000; border: 1px solid #ccc; border-radius: 4px; cursor: pointer; display: inline-flex; align-items: center; gap: 6px;">
        <span>View on</span>
        <img src="images/github-full.png" alt="GitHub Logo" width="55" height="22" style="background: transparent;">
      </button>
    </a>
    <a href="https://public.tableau.com/views/OnlineImpulsiveBuyingBehaviorSurvey/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" target="_blank" style="text-decoration: none;">
      <button style="padding: 6px 12px; background: #f8f8f8; color: #000; border: 1px solid #ccc; border-radius: 4px; cursor: pointer; display: inline-flex; align-items: center; gap: 6px;">
        <span>View on</span>
        <img src="images/tableau-full.png" alt="Tableau Logo" width="102
      " height="22" style="background: transparent;">
      </button>
    </a>
  </div>


## Skills
<div style="border:1px solid #ccc; padding: 10px; border-radius: 5px;">
  <h4 style="display: flex; align-items: center; gap: 10px;">
  <img src="images/excel.png" alt="Microsoft Excel" style="width: 35px; height: auto;">
  Microsoft Excel
  </h4>
  <ul>
    <li>Proficient in using essential formulas such as SUM, AVERAGE, MIN, MAX, and COUNT for performing common calculations and data summaries.</li>
    <li>Capable of applying Data Validation and Conditional Formatting to improve data clarity and ensure consistency.</li>
    <li>Familiar with lookup and conditional functions including VLOOKUP, XLOOKUP, COUNTIFS, SUMIFS, UNIQUE, and FILTER for handling structured data.</li>
    <li>Able to create Pivot Tables and Pivot Charts to present key insights from datasets.
    </li>
  </ul>
</div>


<br>


<div style="border:1px solid #ccc; padding: 10px; border-radius: 5px;">
  <h4 style="display: flex; align-items: center; gap: 10px;">
  <img src="images/sql-database-generic.png" alt="MySQL" style="width:35px; height: auto;">
  SQL
  </h4>
  <ul>
    <li>Familiar with basic Data Definition Language (DDL) and Data Manipulation Language (DML) operations in MySQL, including CREATE, ALTER, DROP, TRUNCATE, SELECT, INSERT INTO, UPDATE, and DELETE.</li>
    <li>Experienced in using aggregate functions such as COUNT, SUM, AVG, MIN, and MAX for summarizing data effectively.</li>
    <li>Able to write and optimize queries using TRIGGER and stored PROCEDURE for automated and reusable data operations.
    </li>
  </ul>
</div>


<br>


<div style="border:1px solid #ccc; padding: 10px; border-radius: 5px;">
  <h4 style="display: flex; align-items: center; gap: 10px;">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python Logo" style="height: 36px;">
  Python
  </h4>
  <ul>
    <li>Able to perform web scraping tasks, including extracting user-generated content from Google Play reviews and YouTube comments.</li>
    <li>Proficient in data preprocessing, including handling missing values, duplicates, outliers, and performing table joins or splits as needed.</li>
    <li>Skilled in descriptive data analysis and visualization using Pandas, Matplotlib, and Seaborn.</li>
    <li>Experienced in preparing data for machine learning through feature engineering, scaling, encoding, and train-test splitting.</li>
    <li>Capable of applying supervised learning models (classification and regression) and unsupervised techniques (clustering and association rule mining).</li>
  </ul>
</div>


<br>


<div style="border:1px solid #ccc; padding: 10px; border-radius: 5px;">
  <h4 style="display: flex; align-items: center; gap: 10px;">
  <img src="images/Tableau.jpg" alt="Tableau" style="width: 35px; height: auto;">
  Tableau
  </h4>
  <ul>
    <li>Able to create basic visualizations such as bar charts, pie charts, and line charts using Tableau Public.</li>
    <li>Capable of customizing visual elements including labels, colors, and tooltips for clear data presentation.</li>
    <li>Experienced in building simple dashboards by combining multiple sheets and applying cross-sheet filters for interactive user experience.</li>
  </ul>
</div>
