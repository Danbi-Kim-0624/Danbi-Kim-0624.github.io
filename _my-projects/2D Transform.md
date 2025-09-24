---
title: "2D Fourier Transform Drawing Machine"
order: 3
layout: posts
permalink: /my-projects/FourierTransformDrawingMachine/
date: 2022-06-30
header:
  teaser: "/assets/images/my-projects-images/AE280-sample-butterfly.png"
  description: "Approximate any given arbitrary path by Fourier Transform on the complex plane"
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
</style>

<p style="text-align:left; color:#888; font-size:0.8em; margin-bottom:20px;">
  {{ page.date | date: "%Y/%m/%d" }}
</p>

### Motivation

<p style="text-align:center;">
  <img src="{{ page.header.teaser }}" alt="Teaser Image" style="width:100%; max-width:600px;">
</p>

I was thinking about what topic to choose for the final project of the AE280 course. While browsing 3Blue1Brown, a math channel I usually watch with interest on YouTube, I came across a video about the Fourier Transform Drawing Machine. It explains how to approximate any given arbitrary path using the Fourier Transform on the complex plane.

The ultimate goal of my project was to reproduce the content presented in this video.

<div class="github-bookmark">
  <div class="bookmark-icon">
    <i class="fab fa-youtube fa-2x" style="color: #FF0000;"></i>
  </div>
  <div class="bookmark-content">
    <h4>But what is a Fourier series? From heat flow to drawing with circles | DE4</h4>
    <p>Check out the full video in YouTube.</p>
    <a href="https://www.youtube.com/watch?v=r6sGWTCMz2k">
      Drawing Machnie using Fourier transform in complex plane
    </a>
  </div>
</div>

### GitHub Page

<div class="github-bookmark">
  <div class="bookmark-icon">
    <i class="fab fa-github fa-2x"></i>
  </div>
  <div class="bookmark-content">
    <h4>2D Fourier Transform Drawing Machine</h4>
    <p>Check out the full code and documentation for this project on GitHub.</p>
    <a href="https://github.com/Danbi-Kim-0624/2D-Fourier-Transform-Drawing-Machine" target="_blank">
      github.com/Danbi-Kim-0624/2D-Fourier-Transform-Drawing-Machine
    </a>
  </div>
</div>
