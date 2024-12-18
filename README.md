# Data Engineering Take-Home Test

## Overview

Build a simple analytics pipeline to process LLM application logs and produce a chart or dashboard. The dataset contains 1,000 API call records with metrics like timestamps, token counts, and latency.

## Instructions

1. Fork this repository
2. Use the provided [data/llm-logs.json](data/llm-logs.json) dataset
3. Create a pipeline that:
   - Loads the JSON data into a database of your choice
   - Calculates some metrics over time
   - Generates at least one visualization or dashboard

You can use any language, database, and visualization tools you want. Don't worry about perfection – we value simplicity and elegance. A quick and simple solution that just works is ideal.

Feel free to ask any questions via github issues or an email to our recruiting team. Good luck!

## Requirements

- Working code that processes the data
- A database to store the transformed data
- At least one chart/visualization
- Replace this README.md with a document explaining your solution and how to run it

## Data Format

```json
{
  "created": "2024-12-18 16:40:40",
  "model": "gpt-4o-2024-11-20",
  "metrics": {
    "tokens": 1213,
    "prompt_tokens": 337,
    "completion_tokens": 876,
    "time_to_first_token": 12.769
  }
}
```
