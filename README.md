# CFC F18 RCOS-Tweets 

Overview:
---

Components:

- Twitter Feed Ingest Layer
- Keyword Analysis Layer
- NLP Layer 
- Disaster Databases
  - 2x staging databases
  - Main datawarehouse
- Logistics Analysis Layer


To Do:
---

1. Use Node-Red to pipe twtiiter data into MongoDB
2. Pipe MDB to Watson to extract keywords
3. On keyword analysis, filter by topics, emotions ,ettc
4. Take clean data, using Node-Red, to send back to 2nd datastore

Repos:
---

`/twitter-ingest` - Streams tweets from twitter into MongoDB, analyze with Jupyter Notebook
