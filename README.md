🧭 Tarjan’s Algorithm — SCC Visualizer

An interactive web tool to visualize Tarjan’s Algorithm for finding Strongly Connected Components (SCCs) in directed graphs.
This project allows you to create nodes, draw edges, and watch the algorithm run step-by-step with real-time highlighting of discovery times, low-link values, stack operations, and SCC formation.

🚀 Features
🎨 Interactive Graph Creation

Click anywhere to add nodes

Select two nodes to add directed edges

Clean UI for building custom graphs quickly

🧠 Tarjan’s Algorithm Visualized

Step-by-step DFS traversal

Real-time update of:

Discovery Time

Low-Link Values

Stack State

Automatic detection & highlighting of SCCs

📘 Learning Mode

Pseudocode panel for easy reference

Explanation for each step

Perfect for students learning Graph Theory or preparing for interviews

📊 Result Panel

All SCCs listed cleanly after execution

Distinct color highlight for each SCC

🛠️ Tech Stack

HTML5

CSS3 (custom theme)

JavaScript (Vanilla)

Canvas/DOM-based graph rendering

📂 Project Structure
/css
    styles.css

/js
    graph.js
    tarjan.js
    ui.js

index.html
README.md

▶️ How to Run

Download or clone the repository:

git clone https://github.com/your-username/tarjan-scc-visualizer.git


Open index.html in any browser

Start creating nodes and edges

Click Run to visualize Tarjan’s algorithm

No dependencies, no installations — works entirely in the browser.


📚 About Tarjan’s Algorithm

Tarjan’s Algorithm is a DFS-based approach to find Strongly Connected Components in a directed graph in O(V + E) time.
It uses:

Discovery times

Low-link values

A stack to track visited nodes

This visualizer helps understand how SCCs are formed and how back edges affect low-link values.

📝 Future Enhancements

Export / import graph as JSON

Add animation speed controls

Add Kosaraju’s algorithm for comparison

Dark & Light mode toggle

Node dragging and rearranging

🙌 Acknowledgements

Built as an educational and visualization tool for Graph Theory learners, competitive programmers, and anyone curious about how Tarjan’s Algorithm works internally.
