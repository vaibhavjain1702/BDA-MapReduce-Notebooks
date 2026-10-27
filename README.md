# BDA MapReduce Notebooks

Python notebooks practicing the MapReduce programming model (map, shuffle and sort, reduce) for the Big Data Analytics course. All code runs locally in plain Python, with no Hadoop cluster required.

## Contents

| File | Description |
|---|---|
| `LinkedIn_mapreduce.ipynb` | Worked examples: counting profile views per user and word count over web pages, with explicit map, shuffle/sort and reduce phases. |
| `mapreduce_linkedin_tasks.ipynb` | Exercises on LinkedIn-style interaction data (content types, top content, connection neighbors), with `YOUR CODE HERE` stubs. |
| `mapreduce_linkedin_solutions.ipynb` | Solutions to the exercises. |
| `sample.csv` | Small toy dataset (`id,value,category`). |

## Running

```bash
pip install jupyter
jupyter notebook
```
