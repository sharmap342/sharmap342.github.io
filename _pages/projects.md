---
permalink: /projects/
layout: single
classes: wide
author_profile: false
# title: "About"
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
      <img src="/path-to-image1.jpg" alt="Project Image 1" style="width: 150px; height: auto; margin-right: 20px;"/>
      <div>
        <h2 style="margin: 0;">Data Science Project 1</h2>
        <p>Short description of the project. For example, a sentiment analysis on tweets.</p>
        <p>
          <a href="https://github.com/your-repo1" target="_blank">GitHub</a> |
          <a href="https://your-project-link1.com" target="_blank">Live Demo</a>
        </p>
      </div>
    </div>

    <!-- Data Engineering Project -->
    <div class="project-item data-engineering" style="display: flex; align-items: center; margin-bottom: 20px;">
      <img src="/path-to-image2.jpg" alt="Project Image 2" style="width: 150px; height: auto; margin-right: 20px;"/>
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
      <img src="/path-to-image3.jpg" alt="Project Image 3" style="width: 150px; height: auto; margin-right: 20px;"/>
      <div>
        <h2 style="margin: 0;">Data Science Project 2</h2>
        <p>Another project description, like developing machine learning models.</p>
        <p>
          <a href="https://github.com/your-repo3" target="_blank">GitHub</a> |
          <a href="https://your-project-link3.com" target="_blank">Live Demo</a>
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