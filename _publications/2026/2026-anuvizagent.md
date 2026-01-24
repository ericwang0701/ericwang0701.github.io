---
title: "AnuVizAgent: A Live AI-Driven Workflow for Immersive Visualization"
date: 2026-01-20
selected: true
type: project
pub: "Ongoing Research Project"
tags: ["# XR", "LLM/VLM", "# Human-Agent Interaction"]
paper_name: "AnuVizAgent"
cover: /assets/images/covers/anuvizagent.png

authors:
  - Cheng-Yao Wang

tldr: >-
  AnuVizAgent enables users to transform raw data into immersive WebXR visualizations through
  natural language interaction, with AI agents generating live, executable visualization code.

abstract: >-
  Creating immersive visualizations typically requires significant expertise in graphics,
  web development, and XR frameworks, posing a high barrier for exploratory data analysis.
  This project explores an interactive workflow that enables users to transform raw datasets
  into immersive, web-based visualizations through natural language interaction.
  
  Users begin by uploading structured data (e.g., CSV or JSON) and iteratively describing
  desired visual outcomes in a chat interface. An AI agent translates these high-level intents
  into executable Anu.js and Babylon.js code, which is injected into a live Vite development
  server and rendered in real time with hot reloading.
  
  Crucially, the same visualization is accessible across devices: users can refine results
  on a desktop browser and seamlessly view the identical, continuously updated scene in a
  WebXR-enabled headset such as Apple Vision Pro via a shared HTTPS endpoint. By combining
  AI-assisted code generation, live web visualization, and device-agnostic delivery,
  AnuVizAgent lowers the barrier to creating and exploring immersive data representations.
---
