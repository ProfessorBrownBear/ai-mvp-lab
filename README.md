# AI/ML Project Lab: Building Our CI/CD Pipeline with GitHub

## Overview and Purpose

Welcome to the AML3304 AI/ML Project Lab! This repository is designed to guide your team through the process of **building a Minimum Viable Product (MVP) of an AI Language Model-driven application**. We will follow a **realistic tech startup pipeline using the AURA Incubator Methodology**, focusing on **product-oriented engineering practices**.

Our goal is to integrate core AI development with modern software engineering disciplines. This involves leveraging **GitHub** as the central hub for source code management, Continuous Integration/Continuous Deployment (CI/CD), and project management, alongside **Hugging Face Spaces** for model deployment and **Google Colab** as our primary development environment.

## Why GitHub as Our Central Hub?

GitHub serves as the **central nervous system** for this project, offering multiple benefits aligned with our learning objectives:

*   **Zero Onboarding Friction**: We are leveraging your existing familiarity with GitHub accounts, repositories, commits, and pushes. This allows us to **teach new concepts like CI/CD and project management** through a **classic scaffolding** approach using a tool you already know.

*   **GitHub Actions for CI/CD**: GitHub Actions provides a **YAML-based, well-documented, and GitHub-native** solution for automating our CI/CD pipeline. This enables **event-driven automation**, transforming our development process and building **muscle memory** for automated workflows. We will use it to **automate the building, testing, and deployment of code changes** directly from our repository.

*   **GitHub Issues for Project Management**: Issues provide **lightweight project scaffolding**, fostering **agile literacy** without the overhead of more complex tools like JIRA. You will learn to **open, tag, assign, and close issues**, instilling habits of **transparency and traceability**. Furthermore, the ability to integrate GitHub Issues with **Power BI for visualized progress tracking** offers a powerful **product engineering mindset** and facilitates **stakeholder communication**, creating a **teachable moment about observability** ("What gets measured gets managed").

## The "Hands-On Imperative": Building It Ourselves

In this course, we embody the **"hands-on imperative"**. Our philosophy is not to simply download or copy pre-built CI/CD pipelines, but to **build our own** from the ground up. This process is crucial for understanding that **systems are not sacred—they are just parts interacting**. By actively **wiring it up, breaking it, fixing it, and wiring it up again**, you will gain a deep, intrinsic understanding of **how it works**. This approach **reduces complexity**, **embeds CI/CD as a fundamental thinking habit**, and reinforces the idea that AI, analytics, and engineering are **mutually informing systems**.

## Project Objectives and Key Deliverables (via GitHub)

This repository will serve as the central point for all project activities and deliverables, directly supporting the AML3304 course learning outcomes:

*   **Source Code Management Systems (Git)**.
*   **Project & Process Management Tools (GitHub Issues)**.
*   **Software Configuration & Continuous Integration (GitHub Actions)**.

Key deliverables that will be developed, housed, or linked from this repository include:

*   **AI Chatbot MVP**: The core functional AI application.
*   **Full Machine Learning Pipeline**: A self-contained pipeline encompassing data preparation, model training, and evaluation.
*   **CI/CD Integration**: Automated deployment from GitHub to Hugging Face Spaces triggered on commits, complete with robust issue tracking.
*   **Product Documentation**: Including this `README.md`, usage guides, prompt design strategy, and inference API details.
*   **UML/System Blueprint**: Diagrams illustrating the model's flow and inference pipeline.
*   **Google NotebookLM Integration**: Our **centralized Body of Knowledge (BoK)**, where we will **construct a virtual AI personality**—your **Project Mentor and AI Architect**. This AI mentor will provide architectural advice, guide engineering decisions, and reflect team learning throughout the project lifecycle. Its ability to demonstrate insight and narrate your journey will be a key part of the project assessment.

## Core Technologies in Action

We will utilize a set of industry-standard tools and platforms:

*   **Google Colab**: For interactive AI model development and training.
*   **Hugging Face Transformers**: To leverage pre-trained models and facilitate easy integration.
*   **PyTorch/TensorFlow**: For underlying model implementation and training.
*   **Gradio**: For building user-friendly web interfaces for our AI application.
*   **GitHub Actions**: Our chosen platform for implementing automated CI/CD workflows.
*   **GitHub Issues**: For Agile project management, sprint planning, feature tracking, and bug reporting.
*   **Google NotebookLM**: For comprehensive project knowledge management and the development of our AI mentor.

## Conceptual CI/CD & Project Management Flow

Our practical workflow will conceptually operate as follows:

*   You will **push code to GitHub** ➝ a **GitHub Action will run tests (e.g., `pytest`)** ➝ and the application will then **deploy to Hugging Face Spaces**.
*   As your team **opens and closes Issues** in GitHub ➝ this data will **auto-update a Power BI dashboard** (to be covered in a later lab) ➝ and the **team will reflect on progress and decisions within Google NotebookLM**, leveraging the AI mentor to summarize learnings.

---

This repository marks the beginning of our **"Build It Yourself"** journey, equipping you with essential, hands-on skills in AI application development, CI/CD, and effective project management.
