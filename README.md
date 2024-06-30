# GPTPersonalFinancing

### Why I need this and not a personal finance app  
* I hate budgeting apps and personal financing apps. Most of them treat me like a 2-year-old. 
* I'm old school in the way that I like using a PC for everything and would rather use a spreadsheet and create my analytics and visualizations than let an app do it. I DESPISE phone UIs. 
* The apps do a terrible job scraping text messages and often confuse transaction messages and authentication messages.

### The plan 
* Take an SMS backup
* Run a python script on it to clean up the data
* Feed the data to an LLM to parse transaction vs authentication messages (if not easily doable through any other means). 
* Get an auto-generated report made by me, for me. 
