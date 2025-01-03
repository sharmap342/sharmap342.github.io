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
    <button onclick="filterProjects('data-science')" 
            style="margin-right: 10px; padding: 10px; background-color: #3498db; color: white; border: none; border-radius: 5px; cursor: pointer;">
        Data Science
    </button>
    <button onclick="filterProjects('data-engineering')" 
            style="padding: 10px; background-color: #27ae60; color: white; border: none; border-radius: 5px; cursor: pointer;">
        Data Engineering
    </button>
    <button onclick="filterProjects('software-engineering')" 
            style="margin-right: 10px; padding: 10px; background-color: #8e44ad; color: white; border: none; border-radius: 5px; cursor: pointer;">
        Software Engineering
    </button>
    <button onclick="filterProjects('all')" 
            style="margin-right: 10px; padding: 10px; background-color: #e67e22; color: white; border: none; border-radius: 5px; cursor: pointer;">
        All
    </button>
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
          <a href="https://youtu.be/00uGaKFoboY" target="_blank">Live Demo</a>
        </p>
      </div>
    </div>

    <!-- Data Engineering Project -->
    <div class="project-item data-engineering data-science" style="display: flex; align-items: center; margin-bottom: 20px;">
      <img src="/assets/images/ddlh.PNG" alt="Project Image 2" style="width: 200px; height: auto; margin-right: 20px; margin-left: 20px;"/>
      <div>
        <h2 style="margin: 0;">Designing a Data Lakehouse for Real-Time Analytics in Banking</h2>
        <p>This project focuses on designing a scalable data lakehouse solution for a major bank to address inefficiencies in data retrieval from its Master Data Management (MDM) system. By integrating Apache Kafka and Hadoop with tools like PySpark, the solution streams real-time data to downstream analytics teams, enabling faster customer segmentation, fraud detection, and credit risk modeling. The new architecture ensures minimal system load and real-time insights for business-critical processes.</p>
        <p>
          <a href="https://github.com/sharmap342/ddlh" target="_blank">GitHub</a> |
          <a href="https://medium.com/@sharmapushpendra342/list/designing-a-data-wareehouse-for-a-big-bank-ae732f83583c" target="_blank">Blog</a>
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

    <!-- Another Data Science Project -->
    <div class="project-item data-science" style="display: flex; align-items: center; margin-bottom: 20px;">
      <img src="/assets/images/jobs.gif" alt="Project Image 3" style="width: 200px; height: auto; margin-right: 20px; margin-left: 20px;"/>
      <div>
        <h2 style="margin: 0;">Web Scraping Data Analyst Job Listings from Indeed</h2>
        <p>This project involves using Beautiful Soup to scrape data analyst job listings from Indeed for the Toronto region. The scraped data, including job titles, companies, and locations, is exported to a CSV file, enabling further analysis and insights.</p>
        <p>
          <a href="https://github.com/sharmap342/Beautiful_Soup_HTML_Web_Scraping" target="_blank">GitHub</a> |
          <a href="https://medium.com/@sharmapushpendra342/scraping-data-analyst-job-listings-from-indeed-52f1d24a09c0" target="_blank">Blog</a>
        </p>
      </div>
    </div>

    <!-- Another Data Science Project -->
    <div class="project-item data-science" style="display: flex; align-items: center; margin-bottom: 20px;">
      <img src="/assets/images/word.gif" alt="Project Image 3" style="width: 200px; height: auto; margin-right: 20px; margin-left: 20px;"/>
      <div>
        <h2 style="margin: 0;">A Word A Day Bot: Personalized Vocabulary Builder</h2>
        <p>Created a Python bot that sends a daily email with a word from a personalized vocabulary list. Leveraged Selenium and Beautiful Soup for web scraping, smtplib for email automation, and Windows Task Scheduler for daily execution, offering a practical approach to vocabulary building tailored to your preferences.</p>
        <p>
          <a href="https://github.com/sharmap342/A_Word_A_Day_Bot" target="_blank">GitHub</a> |
          <a href="https://medium.com/@sharmapushpendra342/developing-a-word-a-day-bot-using-python-6088080e1d12" target= "_blank">Blog</a>
        </p>
      </div>
    </div>

    <!-- Software Engineering Project -->
    <div class="project-item software-engineering" style="display: flex; align-items: center; margin-bottom: 20px;">
      <img src="/assets/images/cutoff.jpg" alt="Project Image 3" style="width: 200px; height: auto; margin-right: 20px; margin-left: 20px;"/>
      <div>
        <h2 style="margin: 0;">Developing a Numerical Framework for Engineering Optimal Seals in Nuclear Waste Repositories</h2>
        <p>Designed and implemented a software-based numerical modeling framework to optimize seal designs for tunnels in deep geological repositories. Utilized ITASCA's FISH language to simulate excavation damage zones (EDZs), assessing the impact of seal geometry, geological settings, material properties, and thermal effects. Identified trapezoidal seals as the most effective in mitigating contaminant transport across various scenarios..</p>
        <p>
          <a href="https://github.com/sharmap342/FISH_Java_Codes_Numerical_Methods" target="_blank">GitHub</a> |
          <a href="https://ys.library.yorku.ca/items/a557bb77-3164-41ae-a75e-11412bf3a1cc" target="_blank">Thesis</a>
        </p>
      </div>
    </div>

    <!-- Software Engineering Project -->
    <div class="project-item software-engineering" style="display: flex; align-items: center; margin-bottom: 20px;">
      <img src="/assets/images/slope.png" alt="Project Image 2" style="width: 200px; height: auto; margin-right: 20px; margin-left: 20px;"/>
      <div>
        <h2 style="margin: 0;">Building a Finite Element Analysis Software Suite for Slope Stability in MATLAB</h2>
        <p>Designed and implemented a modular MATLAB software package for slope stability analysis, leveraging elastic and elasto-plastic finite element methods. The software features automated data preparation, mesh generation, numerical integration, stress-strain visualization, and interactive plotting for analyzing displacement and stress contours.</p>
        <p>
          <a href="https://github.com/sharmap342/Matlab_FEA_Computational_Mechanics" target="_blank">GitHub</a> |
          <a href="https://github.com/sharmap342/FISH_Java_Codes_Numerical_Methods/blob/main/README.md" target="_blank">Report</a>
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
  // Set default category to 'data-science' on page load
  window.onload = function() {
    filterProjects('data-science');
  };
</script>