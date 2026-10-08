# Sheik Mohammed Shaw

Software engineer at Zoho, based in Madurai, India.

For the last four years I've worked on the search side of ManageEngine Log360 and EventLog Analyzer: storing,
indexing and searching large volumes of security logs in Elasticsearch, often down at the Lucene level. Lately I've
been putting LLMs on top of search.

### A few things I've built at Zoho

- Moved Lucene FST term dictionaries off-heap, cutting JVM heap use by about 50%
- Switched high-cardinality filter fields to compressed bitmap indexes, cutting disk use by 40%
- Wrote an Elasticsearch version facade that five other ManageEngine products now use
- Built a reindexing framework that moves live data across Elasticsearch versions without loss
- Designed sync and async REST search APIs, and AWS and GCP log collectors

### On weekends

- [nlsearch](https://github.com/sheikmohammedsha/nlsearch): talk to Elasticsearch in plain English. An Elasticsearch
  plugin where an LLM turns a sentence into a real Elasticsearch call and explains the result. I wrote up how it works
  [on my blog](https://blogs.sheikmohammedsha.shop/2026/10/nlsearch-teaching-elasticsearch-what.html).

### What I work with

**Search and data:** Elasticsearch · Lucene · PostgreSQL · MySQL · MSSQL · Redis · Kafka · Solr

**Languages:** Java · Python · JavaScript · SQL · Bash · Groovy · C

**Backend and web:** REST APIs · Tomcat · EmberJS · Django · HTML / CSS

**Cloud and DevOps:** Docker · Kubernetes · AWS (S3, CloudTrail) · GCP (Cloud Logging) · CI/CD · Git · Gradle · Linux

**AI and ML:** LLM tool use · RAG on Elasticsearch · LangChain4j · Ollama · OpenAI / Anthropic / Gemini APIs · TensorFlow

**Testing:** JUnit · integration testing · JMeter

### Elsewhere

[Portfolio](https://www.sheikmohammedsha.shop) · [Blog](https://blogs.sheikmohammedsha.shop) · [LinkedIn](https://www.linkedin.com/in/sheikmohammedsha) · sheikmohammedsha@gmail.com

Open to agentic AI, LLM and search engineering roles, anywhere.
