---
title: "XRCopilot: A Lightweight and Generalizable Approach for Conversational Interaction in XR"
date: 2025-06-01
selected: true
type: project
pub: "Research Prototype"
tags: ["# XR", "# LLM/VLM"]
paper_name: "XRCopilot"
cover: /assets/images/covers/XRCopilot.png

authors:
  - Cheng-Yao Wang

tldr: >-
  XRCopilot enables conversational interaction in XR by automatically exposing application
  logic and interaction context to language models through a lightweight, code-driven approach.

abstract: >-
  We present XRCopilot, a lightweight and generalizable approach for enabling conversational
  interaction in Extended Reality (XR) environments, including Virtual Reality (VR),
  Augmented Reality (AR), and Mixed Reality (MR). Instead of relying on application-specific
  instrumentation or handcrafted interaction schemas, XRCopilot leverages a TypeScript
  transformer built on the TypeScript Compiler API to automatically extract function comments,
  source code, and call stacks during user interactions in XR applications.
  
  These signals are continuously organized into a Directed Acyclic Graph (DAG) that captures
  the structure of user interactions at runtime. Each node in the DAG represents a function
  invocation together with its semantic and implementation context, allowing language models
  to reason about user actions, system state, and interaction history. By grounding
  conversational agents directly in application execution, XRCopilot provides a scalable
  foundation for building XR conversational interfaces that are transparent, adaptable,
  and reusable across XR systems.
---
