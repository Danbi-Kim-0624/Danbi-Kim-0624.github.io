---
title: "Projects"
permalink: /projects/
layout: single
sidebar: false
show_author_profile: false
collection: projects
entries_layout: grid
classes: wide
---
<style>
    .page__title {
        text-align: center;
    }
    .page__content {
        max-width: 100%;
        margin-left: auto;
        margin-right: auto;
    }
    /* 전체 그리드 컨테이너 */
    .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 2rem;
    padding: 2rem;
    max-width: 1200px; /* Optional, but good for large screens */
    margin-left: auto;
    margin-right: auto;
    }

    /* 개별 카드 스타일 */
    .project-card {
    display: flex;
    flex-direction: column;
    background-color: var(--card-bg-color, #fff); /* CSS 변수 사용 */
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    text-decoration: none;
    color: inherit;
    border: 1px solid var(--border-color, #ddd);
    }

    .project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 12px rgba(0, 0, 0, 0.15);
    }

    /* 이미지 컨테이너 */
    .project-image-container {
        width: 100%;
        height: 150px;
        overflow: hidden;
    }

    .project-card img {
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

     /* 내용 부분 */
    .project-content {
        padding: 1rem;
        display: flex;
        flex-direction: column;
        gap: 0.5rem;
    }

    .project-content h3 {
        margin: 0;
        font-size: 1.1rem;
        font-weight: bold;
    }

    .project-content p {
        margin: 0;
        font-size: 0.9rem;
        color: #555;
    }

    .project-content .year {
        font-size: 0.8rem;
        color: #999;
    }
</style>

<p style="text-align: center;"> This is a list of projects I have participated in or designed myself. In each section, you can learn about my contributions. </p>
---
<div class="project-grid">
  {% for project in site.my-projects %}
    <a href="{{ project.url }}" class="project-card">
      <div class="project-image-container">
        {% if project.header.teaser %}
          <img src="{{ project.header.teaser | relative_url }}" alt="{{ project.title }} preview image">
        {% else %}
          <img src="{{ site.baseurl }}/assets/images/default_thumbnail.jpg" alt="Default project preview image">
        {% endif %}
      </div>
      <div class="project-content">
        <h3>{{ project.title }}</h3>
        {% if project.header.description %}
          <p>{{ project.header.description }}</p>
        {% endif %}
        {% if project.date %}
          <span class="year">{{ project.date | date: "%Y" }}</span>
        {% endif %}
      </div>
    </a>
  {% endfor %}
</div>