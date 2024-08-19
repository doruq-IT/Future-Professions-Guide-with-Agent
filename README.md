# Future_Professions_Guide_Project
## Overview
Tech-Career-Recommender-with-RAG is an AI-powered agent that helps users identify the most promising career paths in the technology sector over the next decade. Leveraging state-of-the-art techniques like Retrieval-Augmented Generation (RAG) and user interaction, this agent not only identifies top professions but also provides personalized career recommendations based on the user’s skills and interests.

## Features
- Top 5 Emerging Tech Professions: Identifies the most promising technology professions based on job growth, technological advancements, industry demand, and salary potential.
- Interactive Queries: Engages with the user to refine analysis based on specific regions, data sources, and key growth factors.
- Personalized Career Recommendations: Suggests career paths tailored to the user’s unique skills and interests.
- Data-Driven Insights: Uses reputable sources like the World Economic Forum, LinkedIn, and McKinsey & Company to back its analysis.
## Architecture
The project is built using the OpenAGI framework and integrates the Gemini LLM for language processing. It employs multiple agents to break down the task into smaller, more manageable sub-tasks, ensuring accurate and detailed results.


## Installation
To get started with the project, follow these steps:
### 1. Clone the repository:
git clone https://github.com/your-username/Future-Professions-Guide-with-Agent.git
cd future_professions_guide_project
### 2. Set up the environment:
- Install the required dependencies:
    pip install -r requirements.txt
- Set up API keys for Tavily and Gemini
  export TAVILY_API_KEY=your-tavily-api-key
  export GOOGLE_API_KEY=your-gemini-api-key
### 3. Run the project:
- Launch the AI agent:
  python run_agent.py
## Usage
### 1. Run the Jupyter Notebook:

- Open future_professions_guide_project.ipynb to explore the project and interact with the agent.
### 2. Get Career Recommendations:

- Provide your skills and interests when prompted, and the agent will suggest relevant career paths based on the latest industry trends.

## Results
The output is presented in a well-structured format and can be exported as CSV or Excel files. The recommendation system provides insights tailored to user inputs, making the results highly relevant and actionable.

## Contribution
We welcome contributions! Please fork this repository and submit a pull request with your changes. For major changes, please open an issue to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any inquiries or support, please reach out via okan.rescue@gmail.com


