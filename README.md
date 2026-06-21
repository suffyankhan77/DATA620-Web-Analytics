# DATA620-Web-Analytics

## Overview

This repository contains coursework for **DATA 620 Web Analytics** at **CUNY School of Professional Studies**.

The course focuses on applying Python-based methods to analyze social networks, text data, and web analytics data. Topics include graph theory, graph visualization, centrality measures, clustering, two-mode networks, natural language processing, word association, topic mining, sentiment analysis, text-based prediction, and final project-based analysis.

This repository is organized to support reproducible assignments, group projects, video presentations, and portfolio-quality documentation.

---

## Course Information

* **Course:** DATA 620 Web Analytics
* **Credits:** 3 graduate credits
* **Program:** M.S. in Data Science, CUNY School of Professional Studies
* **Instructor:** Alain Ledon
* **Primary Tools:** Python, Jupyter Notebook, NetworkX, NLTK, pandas, NumPy, matplotlib, scikit-learn

---

## Group Members

Most DATA 620 assignments and projects are completed as group work.

* Crystal Quezada
* Nana Kwasi Danquah
* Muhammad Suffyan Khan

---

## Repository Structure

```text
DATA620-Web-Analytics/
│
├── assignments/
│   ├── week1_hello_graph_world/
│   ├── week2_part1_graph_visualization/
│   ├── week2_part2_centrality_measure/
│   ├── week3_part2_data_sets/
│   ├── week4_part2_high_frequency_words/
│   └── week5_part2_document_classification/
│
├── environment/
│   ├── sps620env.yml
│   └── DATA620_Environment_Check.ipynb
│
├── projects/
│   ├── project_01/
│   ├── project_02/
│   ├── project_03/
│   └── final_project/
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## Environment Setup

The course environment was created using the provided `sps620env.yml` file.

The environment includes:

* Python 3.7
* NetworkX 1.11
* NLTK
* pandas
* NumPy
* matplotlib
* scikit-learn
* Jupyter Notebook / JupyterLab

To create the environment:

```bash
conda env create -f environment/sps620env.yml
```

To activate the environment:

```bash
conda activate sps620env
```

To launch Jupyter Notebook:

```bash
jupyter notebook
```

The environment was verified using:

```text
environment/DATA620_Environment_Check.ipynb
```

---

## Submission Format

Course assignments and projects are submitted as **Jupyter Notebooks** through GitHub links.

Each notebook is expected to include:

* Assignment or project title
* Team member names
* Objective and problem description
* Step-by-step explanation of the work
* Python code and outputs
* Network or text visualizations
* Interpretation of results
* Video presentation link, when required
* References and attribution for external code or datasets

---

## Coursework Progress

### Assignments

| Assignment    | Topic                   | Folder                                             | Status                              |
| ------------- | ----------------------- | -------------------------------------------------- | ----------------------------------- |
| Week 1        | Hello Graph World       | `assignments/week1_hello_graph_world/`             | Completed                           |
| Week 2 Part 1 | Graph Visualization     | `assignments/week2_part1_graph_visualization/`     | Completed                           |
| Week 2 Part 2 | Centrality Measures     | `assignments/week2_part2_centrality_measure/`      | Document completed; video remaining |
| Week 3 Part 2 | Data Sets               | `assignments/week3_part2_data_sets/`               | Completed                           |
| Week 4 Part 2 | High Frequency Words    | `assignments/week4_part2_high_frequency_words/`    | Incomplete                          |
| Week 5 Part 2 | Document Classification | `assignments/week5_part2_document_classification/` | Incomplete                          |

### Projects

| Project       | Topic                            | Folder                    | Status     |
| ------------- | -------------------------------- | ------------------------- | ---------- |
| Project 1     | Network Analysis Project         | `projects/project_01/`    | Completed  |
| Project 2     | To be determined                 | `projects/project_02/`    | Incomplete |
| Project 3     | To be determined                 | `projects/project_03/`    | Incomplete |
| Final Project | Network Analysis and Text Mining | `projects/final_project/` | Incomplete |

---

## Completed Work

### Week 1: Hello Graph World

The Week 1 assignment introduces basic graph creation and visualization using NetworkX. The notebook demonstrates how nodes and edges can be used to represent relationships in a simple network.

Folder:

```text
assignments/week1_hello_graph_world/
```

Files include:

* `DATA620_Week1_Hello_Graph_World.ipynb`
* `Data620_Assignment_1_Hello_Graph_World.ipynb`
* `W1_Hello_Graph_Group_Video.mp4`

---

### Week 2 Part 1: Graph Visualization

This assignment focuses on graph visualization using NetworkX. It demonstrates how network layouts and visual design choices can help explain graph structure and relationships.

Folder:

```text
assignments/week2_part1_graph_visualization/
```

Files include:

* `Assignment3_Graph_Visualization.ipynb`
* `Assignment3_Graph_Visualization_Video.mp4`

---

### Week 2 Part 2: Centrality Measures

This assignment focuses on centrality measures and how they can be used to analyze important nodes in a network. The written document is complete, and the video presentation is still pending.

Folder:

```text
assignments/week2_part2_centrality_measure/
```

Files include:

* `DATA620_Week2_Part2_Centrality_Measures_Spotify.docx`

---

### Week 3 Part 2: Data Sets

This assignment identifies and discusses network datasets that can be used for analysis. The notebook and video presentation are complete.

Folder:

```text
assignments/week3_part2_data_sets/
```

Files include:

* `W3_Part2_Assignment_Data_Sets.ipynb`
* `W3_P2_Assignment_Data_Sets_Video.mp4`

---

### Project 1

Project 1 applies network analysis concepts using node and edge data. The project folder includes the main Jupyter Notebook, supporting CSV files, and video presentation.

Folder:

```text
projects/project_01/
```

Files include:

* `Data_620_Project_1.ipynb`
* `DATA620_Project1_Video.mp4`
* `nodes.csv`
* `edges.csv`
* `placeholder.txt`

---

## Pending Work

The following items are still incomplete and will be updated as the course progresses:

* Week 2 Part 2 video presentation
* Week 4 Part 2 High Frequency Words
* Week 5 Part 2 Document Classification
* Project 2
* Project 3
* Final Project

---

## Dataset Sources

Potential dataset sources for this course include:

* SNAP Stanford Network Analysis Project
* KONECT Network Collection
* Network Repository
* UCI Network Data Repository
* GroupLens / MovieLens datasets
* Kaggle Datasets
* Google Dataset Search
* Other public web, text, and network datasets as appropriate

---

## Reproducibility

This repository is designed to support reproducible work. Code, notebooks, environment files, and documentation are organized so assignments and projects can be reviewed and rerun when possible.

For external datasets, the repository will include either:

* direct source links,
* instructions for downloading the data, or
* small processed/sample datasets when appropriate and permitted.

---

## Attribution

Any non-trivial external code, datasets, examples, or references used in this repository will be cited in the relevant notebook and/or project documentation.

---

## Author

**Muhammad Suffyan Khan**
M.S. in Data Science
CUNY School of Professional Studies
