# Project 1 Report: Intelligent Search Visualizer

> [!IMPORTANT]
> **AUTOGRADER COMPLIANCE INSTRUCTIONS:**
> This report is parsed automatically by the autograder. To ensure you receive full credit for your work:
> 1. **Do not modify** the section headers (`## ...`) or bold field keys (e.g., `**Name:**`, `**Selected Region:**`, `**Live Deployment URL:**`, etc.).
> 2. **Write your answers directly after** the colon `:` of each field, replacing the placeholder text completely (including the outer brackets `[` and `]`).
> 3. **Maintain the file structure**. Changing headers, bold titles, or deleting lines can cause the autograder to miss your responses and award 0 marks.

---

## Student Information 
- **Name:** Youssef Elghawabi
- **UID (netID):** yelgh2
- **UIN:** 676467851

---

## Section 1: Selected City Region
- **Selected Region:** Illinois

---

## Section 2: Map Graph Configuration
- **Total Cities Configured:** 22
- **Total Connection Edges:** 35
- **Graph Fully Connected:** Yes

---

## Section 3: Local Verification & Search Algorithms
*Check the algorithms you successfully ran and verified on your local development server by placing an `x` in the brackets (e.g., `[x]`):*
- [X] Breadth-First Search (BFS)
- [X] Depth-First Search (DFS)
- [X] Uniform Cost Search (UCS)
- [X] Iterative Deepening Search (IDS)
- [X] Greedy Best-First Search (Greedy)
- [X] A* Search (A*)

---

## Section 4: Deployed and Presentation Information
- **Deployment Platform:** Render
- **Live Deployment URL:** [Provide your live deployment site URL here]
- **Video Presentation Link:** [Provide an accessible link to your 5–7 minute video presentation]

---

## Section 5: Discussion
- **Which search algorithm is best for this route finding problem?** 
    A* is the best because when I ran multiple search paths, for example, from Chicago to Rockford, the A* search and greedy had the lowest total cost out of all other searches. A* is better than greedy because even though they have the same total cost, A* finds the path in less nodes expanded.
- **Search Efficiency (Nodes expanded/time taken comparison):** [Write your answer here comparing search efficiency in terms of number of snodes visited and runtime across different algorithms]
- **Link the idea of search algorithm to today Generative AI.** 
    Search algorithms are used for Generative AI because have to choose between many options to find the best possible output based on probabilities. The algorithm explores different possible paths and uses data to decide which path to use next similar to search algorithms like A* and greedy search. So, they are very similar in how they are searching through a large number of possibilities.

