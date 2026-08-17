---
layout: about
title: about
permalink: /
subtitle: Computer Science Student • University of Utah

profile:
  align: right
  image: 
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Salt Lake City, Utah 84102</p>

selected_papers: false # no academic publications yet - re-enable once _bibliography/papers.bib has real entries
social: true # includes social icons at the bottom of the page

research_statement: >
  A collection of my software projects spanning machine learning, game development, and NLP. More on <a href="https://github.com/SimonVo05" target="_blank">GitHub</a>.

education:
  enabled: true
  items:
    - school: University of Utah
      degree: Bachelor of Science in Computer Science, Minor in Mathematics
      dates: Expected May 2027
      details: "GPA: 3.9 | Dean's List (2023–Present) | Utah Global Scholarship Recipient"
      coursework: "Relevant coursework: Algorithms, Computer Systems, Object-Oriented Programming, Introduction to Machine Learning, Foundation of Analysis."

skills:
  enabled: true
  categories:
    - title: Coding Languages
      items: Python, Java, C++, C#, HTML, CSS, Assembly
    - title: Libraries/Tools
      items: scikit-learn, pandas, PyTorch, Qt, Streamlit, Flask, Git, Kaggle, REST APIs
    - title: Core Concepts
      items: Data structures and algorithms, software design, machine learning, model evaluation, API integration, backend services, data processing pipelines, debugging, testing, and collaborative development

experience:
  enabled: true
  items:
    - title: Teaching Assistant
      org: University of Utah
      dates: Aug 2025 – Present
      bullets:
        - Support a class of 100+ students in software practice by answering questions, explaining programming concepts, and reinforcing core software engineering fundamentals.
        - Provide one-on-one guidance during labs and office hours, helping students debug code, improve problem-solving skills, and better understand assignments.
        - Assist with grading assignments and exams while communicating feedback clearly and consistently.
    - title: Food Service Worker
      org: University of Utah
      dates: Aug 2024 – Aug 2025
      bullets:
        - Worked in a fast-paced, customer-facing environment, handling requests efficiently and resolving issues professionally.
        - Built strong communication and teamwork skills by collaborating with coworkers and serving people from diverse backgrounds.

projects:
  enabled: true
  github: https://github.com/SimonVo05
  items:
    - title: World Cup 2026 Prediction Model
      tech: Python, scikit-learn, pandas, Streamlit/Flask
      dates: "2026"
      bullets:
        - Built an end-to-end soccer prediction system using 25,000+ international match records to predict win/draw/loss probabilities, expected goals, over/under goals, and both-teams-to-score probability from two team names.
        - Engineered 40+ model features from Elo ratings, recent 5- and 10-match form, rest days, neutral venue, match type, and FC26 attack/defense/GK player-rating signals.
        - Trained Logistic Regression and Poisson Regression models with chronological 80/20 validation; created repeatable raw-to-processed data pipelines and prediction functions designed for Streamlit/Flask UI integration.
    - title: Magic Tutorial Game
      tech: C++, Qt
      dates: Jan 2025 – May 2025
      bullets:
        - Built an interactive Magic&#58; The Gathering-style tutorial game with automated turn, phase, zone, and stack management.
        - Integrated a card API manager for dynamic card data and designed a custom Qt UI with game board, dialogs, tooltips, and animations.
        - Added a bot opponent and Box2D drag-and-drop interactions while applying object-oriented design to keep gameplay logic maintainable.
    - title: AI vs Human Text Classification
      tech: PyTorch
      dates: Oct 2025 – Nov 2025
      bullets:
        - Trained a 2-layer LSTM text classifier on 50,000 Kaggle text samples, using a 10,000-word vocabulary and 500-token padded sequences to distinguish AI-generated from human-written text.
        - Ran 9 hyperparameter experiments across hidden size and learning rate, achieving 98.2% best validation accuracy and 97.4% final accuracy.
        - Tested transfer learning with a 1,367-sample secondary dataset, then fine-tuned on the main dataset and reached 97.9% accuracy after training.

competitions:
  enabled: true
  items:
    - title: ICPC Regional Programming Contest
      description: Competed in a team-based programming contest focused on algorithms, data structures, and problem-solving under time constraints.

announcements:
  enabled: false # placeholder template news items - enable once _news/ has real entries
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

awards:
  enabled: true
  items:
    - year: 2025
      description: 1st Place, Best Educational App — Crimson Hack by Redo Builder
    - year: 2023–Present
      description: Dean's List, University of Utah
    - year: 2023–Present
      description: Utah Global Scholarship Recipient

services:
  enabled: true
  items:
    - title: Teaching Assistant
      org: University of Utah, Kahlert school of computing

miscellaneous:
  enabled: true
  items:
    - Check out more of my work on [GitHub](https://github.com/SimonVo05).
---

I'm a Computer Science student (minoring in Mathematics) at the University of Utah, expected to graduate in May 2027. I'm interested in machine learning, software engineering, and building end-to-end projects — from prediction models to interactive applications. I currently work as a Teaching Assistant, helping students build strong software engineering fundamentals.
