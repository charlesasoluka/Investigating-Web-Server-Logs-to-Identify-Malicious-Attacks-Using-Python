# Investigating Web Server Logs to Identify Malicious Attacks Using Python

Have you ever wondered how much your web server logs can tell you about what’s really happening on your system — both good and bad?  
This project dives into exactly that: using Python to sift through server logs, uncover patterns, and spot signs of potentially **malicious activity**.

---

## 🧠 Project Overview

This notebook walks you through the process of analyzing raw web server logs to gain insight into who’s been accessing your web application and how.  
By combining data science techniques with a bit of cybersecurity intuition, it helps identify unusual or suspicious patterns that might indicate an attack or system misuse.

Here’s what this project covers step-by-step:

1. **Setting up the environment** — installing and importing essential libraries like `pandas`, `numpy`, `networkx`, and `matplotlib`.
2. **Loading real log data** — reading text-based web logs into Python for structured analysis.
3. **Cleaning and preprocessing** — formatting timestamps, handling missing data, and shaping the dataset for exploration.
4. **Analyzing traffic behavior** — checking how often each client IP address hits the server.
5. **Detecting anomalies** — identifying access patterns that could point to malicious intent (e.g., repeated access from the same IP in short intervals).
6. **Visualizing relationships** — using `networkx` to create a graph that shows how clients interact with the server.

The end result is a structured approach to understanding web server behavior and flagging potential threats — all within a single, reproducible Jupyter notebook.

---

## ⚙️ Requirements

To run this notebook smoothly, make sure you have **Python 3.8 or later** installed on your machine.

You’ll need a few key libraries for data handling and visualization:

```bash
pandas
numpy
networkx
matplotlib


