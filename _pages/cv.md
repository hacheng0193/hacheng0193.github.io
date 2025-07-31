---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Electrical Engineering (Double Major in Computer Science), National Yang Ming Chiao Tung University (NYCU), Hsinchu, Taiwan, Sep 2022 – Present
  * GPA: 4.08/4.30 (3.92/4.00)
  * Courses: ML, NLP, Data Science, Computer Architecture, Operating Systems, Algorithms, Object-Oriented Programming, Data Structures, Computer Architecture, Microcomputer Systems and Lab, Probability, Digital Signal Processing, Computer Networks,
* Exchange Program, University of Illinois at Urbana-Champaign (UIUC), Jan 2025 – May 2025
  * Courses: Text Information, Applied Parallel Programming, Algorithm, Real World IoT Algorithm
  * Strengthened practical skills in CUDA, text retrieval and generation, and cross-cultural communication.

Work Experience
======
* Intern Software Engineer, VIVOTEK Inc., Jan 2024 – Feb 2024
  * Researched and prototyped the integration of Large Language Models (LLMs) with Retrieval-Augmented Generation (RAG) for intelligent FAQ chatbot systems.
  * Built automation tools to process internal manuals and generate context-aware responses for customer support queries.

Research Experience
======
* Financial Knowledge Graph with LLMs, Advisor: Prof. Hong-Han Shuai, Sep 2024 – Jan 2025
  * Designed a pipeline to extract structured financial entities from unstructured PDFs of company reports using LLM-powered prompt workflows.
  * Constructed knowledge graphs and applied them as contextual input for RAG-based LLM applications.

Projects
======
* PvZ Duel (github.com/hacheng0193/aoop-proj-g3-pvz), Jan 2025
  * Created a multiplayer PvZ clone using Pygame where players control either plants or zombies.
  * Applied object-oriented programming (OOP) principles to build a modular, maintainable, and readable codebase.
* Flutter Speech-to-Summary (github.com/hacheng0193/flutter speech-to-summary), July 2024
  * Built a cross-platform mobile app using Flutter and Dart for summarizing audio files or YouTube videos.
  * Implemented automatic transcription and note generation using LLM integration.
* STM32F4 Bejeweled Game (github.com/hacheng0193/STM32F4-Term-Project-Bejeweled-Game), June 2023
  * Implemented core Bejeweled game logic (tile swap, match detection, scoring) on STM32F407VG.
  * Integrated an ILI9341 touch screen for both graphical output and user input via touch gestures.
  * Developed in C/C++ using Keil MDK-ARM development tools.
* FPGA Tetris (IMU Tilt Control) (github.com/hacheng0193/FPGA-final-project-Tetris), May 2023
  * Developed a fully functional Tetris game in Verilog for Nexys DDR4 (Artix-7) FPGA.
  * Used onboard MPU-6050 IMU via SPI to enable tilt-based left/right movement.

Skills
======
* Languages/Tools: Python, C/C++, HTML5, CSS, Git, Flutter
* Tech/Fields: Machine Learning, NLP, LLM, RAG, Prompt Engineering, Data Mining, Web Crawling
* Languages: English(TOEFL 100, TOEIC 960)

Activities & Leadership
======
* President, Go Club, NYCU, Sep 2023 – Aug 2024
  * Planned and led weekly club sessions, organized new student orientation, managed exhibition booth, and coordinated the Mei-Chu Go exhibition match.
* Sports Participation, Active member of EE department’s baseball, badminton, and table tennis teams.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
