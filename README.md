# crewAI

## About 

[**CrewAI**](https://crewai.net/) is a collaborative working system designed to enable various artificial intelligence agents to work together as a team to efficiently accomplish complex tasks.

Suffice it to say that the documentation of [crewAI](https://docs.crewai.com/) is actually written by a crew!

In this repo I've added all the practical examples explained in the insightful-short course introduced from DeepLearning.ai, [Multi AI Agent Systems with crewAI](https://learn.deeplearning.ai/courses/multi-ai-agent-systems-with-crewai/lesson/1/introduction), and due to the code explained in the course depends on OpenAI token and I don't have a pro account, I've modified some line to use Google Gemeni API instead as it's free!


## Content

- **L2**: contains a notebook that implements a nice multi-agent system to generate articles about a specific topic. It has three agents: `planner`, `writer`, and `editor` and tasks for each agent.
- 

## Usage

Steps to use this code on your machine:

1. Clone the repo:
    ``` bash
    git clone git@github.com:mohamedhassan218/hello-crewAI.git
    ```

2. Create a virtual environment:
    ```bash
    python -m venv .venv
    ```

3. Activate your virtual environment:
    - On Windows:
        ```bash
        .venv\Scripts\activate
        ```

    - On Unix or MacOS:
        ```bash
        source .venv/bin/activate
        ```

4. Install the dependencies:
    ``` bash
    pip install -r requirements.txt
    ```

5. Set up environment variables:
    Create a `.env` file in the project root and add the following:
    ```
    GOOGLE_API_KEY=""
    ```
    Get your free API key from [here](https://ai.google.dev/gemini-api/docs/api-key)

6. And now ensure to connect the notebook to your `venv` and try the code yourself.


## Acknowledgement

This platform has been instrumental in advancing my knowledge and practical abilities in AI and machine learning. I would like to express my deepest gratitude to [**DeepLearning.ai**](https://www.deeplearning.ai/) for providing an exceptional learning experience through their course on Multi AI Agent Systems. The insightful lessons and hands-on coding exercises have significantly enhanced my understanding and skills in this area. A special thanks to the team at DeepLearning.ai for their dedication to making high-quality AI education accessible to everyone.