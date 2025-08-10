The Autonomous Data Analyst Agent
An intelligent API that uses LLMs to autonomously source, prepare, analyze, and visualize any data on demand.

Key Metrics
Metric

Value

Description

Response Time

≤ 3 min

Average time to complete an analysis task.

Scalability

1 TB+

Capable of handling terabyte-level datasets.

Operation

100%

Fully autonomous from request to response.

How It Works: The Core Workflow
A simple, four-step process powers the agent's analytical capabilities.

1. API Request 📝

POST request with questions & optional data files.

→

2. Agent Orchestration 🤖

LLM interprets the request and generates a Python analysis plan.

→

3. Tool Execution 🛠️

Runs code in a secure sandbox, using tools for scraping or plotting.

→

4. Synthesize & Respond 📊

Formats results, including Base64 charts, into a final JSON response.

Versatile Capabilities
The agent is engineered to handle a diverse range of data sources and analytical tasks. From scraping live web data to querying large databases and analyzing uploaded files, its capabilities are broad and adaptable. The radar chart illustrates the agent's proficiency across key operational domains, showcasing its balanced strength in data sourcing, processing, and visualization.

Chart Data: Agent Proficiency (Radar Chart)

Web Scraping: 90%

Data Cleaning: 85%

Statistical Analysis: 80%

Database Querying: 75%

Plotting & Visualization: 95%

A Look Inside: The Technology Stack
Built on a modern, high-performance stack, the agent combines the best of AI, data science, and web technologies. The core is powered by Python, with FastAPI serving the API. LangChain orchestrates the interaction with the Gemini LLM, while Pandas and Matplotlib handle the heavy lifting of data manipulation and visualization, ensuring robust and scalable performance.

Chart Data: Technology Stack Composition (Doughnut Chart)

Backend (FastAPI, Python): 40%

AI & Orchestration (LangChain, Gemini): 35%

Data Science (Pandas, Matplotlib): 25%

Use Case: Film Data Analysis
In a sample task, the agent was asked to scrape Wikipedia for the highest-grossing films and analyze the data. One query involved finding the correlation between a film's all-time rank and its peak rank. The agent generated and executed code to produce a scatter plot, revealing a strong positive correlation and fitting a regression line to visualize the trend, all within minutes.

Chart Description: Film Rank vs. Peak (Scatter Plot)

The chart plots 50 sample data points showing a film's all-time box office rank against its peak rank.

A strong positive correlation is visible, with points clustering along a diagonal line.

A regression line is fitted to the data, clearly illustrating the upward trend.

The Evaluation Process
Performance is measured against a rigorous 20-point rubric. This automated evaluation ensures accuracy, structural integrity, and the quality of visualizations. The scoring is broken down into distinct checks: Python-based validation for numerical and text answers, and an advanced LLM-based rubric to grade the generated plots on multiple criteria, including axis labels and visual correctness.

Chart Data: Points Awarded per Evaluation Task (Bar Chart)

Answer 1 ($2bn films before 2000): 4 points

Answer 2 (Earliest $1.5bn film): 4 points

Answer 3 (Rank/Peak Correlation): 4 points

Answer 4 (Scatter Plot Vision Check): 8 points

Autonomous Data Analyst Agent | 2025
