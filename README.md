# CS50 AI 2024 – Degrees of Separation

This repository contains my solution to Project 0: Degrees from Harvard's [CS50's Introduction to Artificial Intelligence with Python (2024)](https://cs50.harvard.edu/ai/2024/). The project focuses on using graph search to solve the "Six Degrees of Kevin Bacon" problem — determining the shortest path of co-stars that connect two actors.

## 🧠 Project Overview
- Uses a breadth-first search (BFS) algorithm to find the shortest connection between two actors.
- Models a dataset of people and movies as an undirected graph.
- Demonstrates fundamental AI concepts like search algorithms and graph traversal.

## 📁 Files
- `degrees.py` – Main program for finding the shortest connection.
- `util.py` – Queue and Stack classes used in the search process.
- `large/` – Dataset of actors and movies (provided by CS50).
- `small/` - Smaller dataset of actors and movies for testing purposes
- Other files - Provided by CS50

## ▶️ How to Run
```bash
python degrees.py
