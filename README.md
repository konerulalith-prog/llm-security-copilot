# LLM Powered Security Copilot  

# Project Overview

This project implements a hybrid security copilot system designed to assist in the interpretation of Linux authentication logs.

The system focuses on detecting repeated failed login attempts and generating clear, structured explanations of suspicious authentication activity.

# Project Development Stages

# Project Development-1

This phase included:

1.  Downloading the Linux authentication log dataset (LogHub)
2. Loading logs using Python
3.  Filtering authentication-related events
4. Displaying suspicious log entries

This stage established the preprocessing and data foundation of the system.

# Project Development-2

This phase expanded the system by adding:

1. Rule-based detection of repeated failed login attempts
2. Identification of possible brute force behavior
3. Natural language explanation generation
4. Interactive query interface for user input

The system now analyzes filtered logs and produces structured explanations in response to security related questions.

# System Architecture

Raw Logs  
1. Keyword-Based Filtering  
2. Authentication Pattern Detection  
3. Explanation Generation  
4. Interactive Security Copilot Interface  

# Example Queries

1. Summarize suspicious activity
2. Are there repeated failed login attempts?
3. Is there brute force behavior?

# Design Approach

A lightweight and reproducible implementation was selected instead of relying on large external API-based models. 

This ensures:

1. Cost efficiency
2. Stable and consistent outputs
3. Easy reproducibility for academic evaluation
4. Clear and explainable system behavior

# Future Work (Evaluation Phase)

The final phase will focus on:

1. Structured evaluation scenarios
2. Assessing interpretability and clarity
3. Comparing system output with raw log analysis
4. Documenting strengths and limitations
