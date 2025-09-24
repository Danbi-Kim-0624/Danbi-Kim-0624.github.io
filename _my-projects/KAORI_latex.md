---
title: "KAORI Booklet by LaTeX"
order : 2
layout: posts
permalink: /my-projects/KAORI-booklet-LaTeX/
date: 2025-09-01
header:
  teaser: "/assets/images/my-projects-images/kaori-booklet-latex-screenshot.png"
  description: "Automate heat sheet generation with Python and output in LaTeX format"
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

### Introduction

<p style="text-align:center;">
  <img src="{{ page.header.teaser }}" alt="Teaser Image" style="width:100%; max-width:600px;">
</p>

I led a project to convert the booklet for the KAIST Swimming Competition, hosted by the KAIST swimming club "[KAORI](https://www.kaist-kaori.org)", from a Hangeul file to a **LaTeX-based** format.
By switching to LaTeX, we were able to separate the booklet into a clear file tree structure, which was impossible with the previous Hangeul file.
It makes much easier for team members to edit.
In particular, I contributed to automate the process of creating the **heat sheets** using Python.

카이스트 수영 동아리 가오리에서 주최하는 카이스트 수영대회의 책자를 한글 파일에서 LaTeX을 이용한 방식으로 바꾸는 프로젝트를 주도했습니다.
기존의 한글 파일에서는 한 눈에 들어오는 파일 트리 구조로 분리가 불가능했던 책자를 LaTeX 형식으로 바꾸며 팀원들이 편리하게 편집할 수 있게 되었습니다.
특히 대진표를 만드는 과정에서 파이썬 코드를 이용해 자동화를 이뤘습니다.

### Automation by Python

<div class="github-bookmark">
  <div class="bookmark-icon">
    <i class="fab fa-github fa-2x"></i>
  </div>
  <div class="bookmark-content">
    <h4>KAORI_Booklet_LaTeX</h4>
    <p>Check out the full code and documentation for this project on GitHub.</p>
    <a href="https://github.com/Danbi-Kim-0624/KAORI_Booklet_LaTeX" target="_blank">
      github.com/Danbi-Kim-0624/KAORI_Booklet_LaTeX
    </a>
  </div>
</div>

### What's Next?

This project was later integrated into the official KAORI website, [https://www.kaist-kaori.org/](https://www.kaist-kaori.org), as part of a larger initiative to automate the entire swimming competition process, from registration to automated heat sheets generation.

해당 프로젝트는 이후 가오리의 공식 홈페이지 [https://www.kaist-kaori.org/](https://www.kaist-kaori.org)의 내부 코드로 활용되어 수영대회의 신청부터 대진표 생성까지의 전체 프로세스를 자동화하는 프로젝트로 이어집니다. 
