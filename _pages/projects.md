---
permalink: /projects/
layout: default
classes: wide
author_profile: false
title: "Projects"
---

<div class="full-width-projects">
  <!-- Filter Navigation -->
  <div style="margin-bottom: 20px; text-align: center;">
    <button onclick="filterProjects('all')" style="margin-right: 10px; padding: 10px;">All</button>
    <button onclick="filterProjects('data-science')" style="margin-right: 10px; padding: 10px;">Data Science</button>
    <button onclick="filterProjects('data-engineering')" style="padding: 10px;">Data Engineering</button>
  </div>

  <!-- Project List -->
  <div class="project" id="project-container">
    <!-- Data Science Project -->
    <div class="project-item data-science" style="display: flex; align-items: center; margin-bottom: 20px;">
      <img src="/assets/images/senti.gif" alt="Project Image 1" style="width: 200px; height: auto; margin-right: 20px; margin-left: 20px;"/>
      <div>
        <h2 style="margin: 0;">Real-Time Sentiment Analysis on Twitter Data</h2>
        <p>Developed a real-time sentiment analysis application that processes Twitter data using machine learning models like Logistic Regression, XGBoost, and neural networks. Cleaned and transformed 1.6 million tweets with regex and NLTK to improve model accuracy, leveraging scikit-learn and Keras for text classification.</p>
        <p>
          <a href="https://github.com/sharmap342/Sentiment_Analyzer_App" target="_blank">GitHub</a> |
          <a href="https://your-project-link1.com" target="_blank">Live Demo</a>
        </p>
      </div>
    </div>

    <!-- Data Engineering Project -->
    <div class="project-item data-engineering" style="display: flex; align-items: center; margin-bottom: 20px;">
      <img src="/assets/images/tohp.gif" alt="Project Image 2" style="width: 150px; height: auto; margin-right: 20px; margin-left: 20px;"/>
      <div>
        <h2 style="margin: 0;">Data Engineering Project 1</h2>
        <p>Description about building ETL pipelines or automation with Azure Data Factory.</p>
        <p>
          <a href="https://github.com/your-repo2" target="_blank">GitHub</a> |
          <a href="https://your-project-link2.com" target="_blank">Live Demo</a>
        </p>
      </div>
    </div>

    <!-- Another Data Science Project -->
    <div class="project-item data-science" style="display: flex; align-items: center; margin-bottom: 20px;">
      <img src="/assets/images/tohp.gif" alt="Project Image 3" style="width: 200px; height: auto; margin-right: 20px; margin-left: 20px;"/>
      <div>
        <h2 style="margin: 0;">Exploring Toronto's Housing Market: Data Analysis and Visualization</h2>
        <p>This project investigates the causes of high housing prices in Toronto through exploratory data analysis and interactive visualizations. Housing data was scraped from PDF files provided by the Toronto Regional Real Estate Board, cleaned, and transformed into CSV format for analysis. The project includes insights into housing prices across different city areas and features a Streamlit-based app for interactive visualization, enhancing user understanding of market trends.</p>
        <p>
          <a href="https://github.com/sharmap342/Why_High_Housing_Prices_Toronto" target="_blank">GitHub</a> |
          <a href="https://sharmap342-why-high-housing-prices-toronto-srcapp-s0vod1.streamlit.app/" target="_blank">Live App</a>
        </p>
      </div>
    </div>
  </div>
</div>

<script>
  // JavaScript Function to Filter Projects
  function filterProjects(category) {
    const projects = document.querySelectorAll('.project-item');
    projects.forEach(project => {
      if (category === 'all' || project.classList.contains(category)) {
        project.style.display = 'flex';
      } else {
        project.style.display = 'none';
      }
    });
  }
</script>