---
title: "Mini Pygame Project with KSOP"
order: 1
layout: posts
permalink: /my-projects/test_project1/
date: 2022-07-01
header:
  teaser: "/assets/images/my-projects-images/start_screen_capture.png"
  description: "Develop a mini Pygame project as part of the KSOP CS curriculum for middle and high school students"
---

<style>
  .page__content {
    max-width : 1000px;
  }
  .github-bookmark {
    display: flex;
    align-items: center;
    border: 1px solid #e1e4e8;
    border-radius: 6px;
    padding: 16px;
    margin: 16px 0;
    box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05);
    transition: box-shadow 0.2s ease-in-out;
  }

  .github-bookmark:hover {
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  .bookmark-icon {
    margin-right: 16px;
    color: #24292e; /* GitHub dark color */
  }

  .bookmark-content h4 {
    margin-top: 0;
    margin-bottom: 4px;
  }

  .bookmark-content p {
    margin: 0;
    font-size: 14px;
    color: #586069;
  }

  .bookmark-content a {
    text-decoration: none;
    font-size: 14px;
    color: #0366d6;
  }
  .video-wrapper {
    position: relative;
    padding-bottom: 56.25%; /* 16:9 화면 비율 (height / width = 9/16 = 0.5625) */
    height: 0;
    overflow: hidden;
    margin-bottom: 1.5rem; /* 영상 아래 여백 추가 */
    max-width: 100%; /* 부모 컨테이너 너비에 맞춤 */
  }
  .video-wrapper iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
</style>

<p style="text-align:left; color:#888; font-size:0.8em; margin-bottom:20px;">
  {{ page.date | date: "%Y/%m/%d" }}
</p>

### Introduction

<p style="text-align:center;">
  <img src="{{ page.header.teaser }}" alt="Teaser Image" style="width:100%; max-width:600px;">
</p>

This is the project to make educational content for KSOP students.
The students had learned the basic game alogithm step by step.

**Features**:
- Control a character that moves left and right with arrow keys
- Dodge falling stones and collect jewels
- Score tracking with clear UI
- Start, How-to, and Game Over screens with engaging graphics


### GitHub Page

<div class="github-bookmark">
  <div class="bookmark-icon">
    <i class="fab fa-github fa-2x"></i>
  </div>
  <div class="bookmark-content">
    <h4>KAORI_Booklet_LaTeX</h4>
    <p>Check out the full code and documentation for this project on GitHub.</p>
    <a href="https://github.com/Danbi-Kim-0624/Mini_Pygame_Project/" target="_blank">
      github.com/Danbi-Kim-0624/Mini_Pygame_Project
    </a>
  </div>
</div>

### YouTube Demo Video

<div class="video-wrapper">
  <iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/embed/aqaAdZVTrz0" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
  </iframe>
</div>