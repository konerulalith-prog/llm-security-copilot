# LLM Powered Security Copilot

## Project Overview

This project presents a hybrid security copilot designed to help interpret Linux authentication logs.

The system focuses on identifying repeated failed login attempts and generating clear explanations of suspicious authentication activity in simple language.

---

## Project Development-1

In the first phase, the focus was on building the data foundation:

1. Downloading the Linux authentication log dataset (LogHub)
2. Loading logs using Python
3. Filtering authentication-related events
4. Displaying suspicious log entries

This stage prepared the logs for structured analysis.

---

## Project Development-2

In the second phase, the system was expanded by adding:

1. Rule-based detection of repeated failed login attempts
2. Identification of possible brute-force behavior
3. Natural language explanation generation
4. An interactive query interface

The system now analyzes filtered logs and provides structured explanations based on user questions.

---

## System Architecture

Raw Logs  
→ Keyword Filtering  
→ Authentication Pattern Detection  
→ Explanation Generation  
→ Interactive Query Interface  

---

## Example Questions

1. Summarize suspicious activity  
2. Are there repeated failed login attempts?  
3. Is there brute-force behavior?  

---

## Final Evaluation

The system was tested using different authentication log scenarios:

1. Logs with many repeated failed login attempts
2. Logs with fewer failed attempts
3. Logs with both failed and successful logins

The system consistently detected repeated failures and clearly explained suspicious patterns. Compared to raw log entries, the explanations were easier to understand.

---

## Design Decision

During development, large language model integration was explored. However, external API-based models require usage costs and introduce reproducibility challenges.

For this academic project, a lightweight hybrid approach was selected to ensure stable behavior, reproducibility, and clear evaluation.

---

## Limitations

- The detection logic is rule based.
- The system focuses only on authentication related logs.
- It does not perform real time monitoring.
