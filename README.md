# Multi-Agent AI Researcher Powered by DeepSeek-R1 LLM Model 🔍🤖

## Overview
The **Multi-Agent AI Researcher** is a Streamlit application that leverages **GroqChat** and **HackerNews tools** to provide in-depth research and analysis of HackerNews stories and user profiles. Designed for researchers, analysts, and enthusiasts, this app offers a collaborative AI-driven team that generates insights, trends, and content based on HackerNews data.

---

## Key Features
- **Multi-Agent Collaboration**: Includes specialized AI assistants for story and user analysis.
- **GroqChat Integration**: Powered by the **deepseek-r1-distill-llama-70b** model for detailed, insightful responses.
- **HackerNews Tools**: Analyzes HackerNews stories, profiles, and trends.
- **Customizable System Prompt**: Ensures responses are detailed, insightful, and actionable.
- **Streamlit Interface**: Simple, user-friendly design for seamless interaction.

---

## Installation

### Prerequisites
Ensure Python 3.8 or higher is installed.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/multi-agent-researcher.git
   cd multi-agent-researcher
   ```

2. Install dependencies:
   ```bash
   pip install phi streamlit
   ```

3. Set up your Groq API key:
   - Enter the key in the app's input field after launching.

---

## Usage

1. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

2. **Interface**:
   - Enter your **Groq API Key**.
   - Input your research query related to HackerNews stories or users.
   - Click **Generate Insights** to receive a detailed response.

---

## Technical Details

### AI Assistants
- **HackerNews Story Researcher**:
  - Analyzes top stories on HackerNews.
  - Provides trends, context, and significance of stories.
- **HackerNews User Researcher**:
  - Examines user profiles, contributions, and influence within the community.
- **HackerNews Insights Team**:
  - A collaborative assistant leveraging **GroqChat** for combined story and user analysis.

### System Prompt Highlights
The system prompt ensures:
- Responses are context-rich and data-supported.
- Insights are framed in the broader context of technology and society.
- Suggestions for further exploration are provided.

### Example Workflow
1. **Query**: "What are the emerging trends in AI from HackerNews stories?"
2. **Response**:
   - Analysis of top stories tagged with AI.
   - Insights into the frequency and themes of AI-related discussions.
   - Broader implications for the tech industry.

---

## Screenshots
- **Homepage**: Input fields for API key and research query.
- **Insights**: Detailed responses displayed in markdown.

---

## Future Enhancements
- Add visualization tools to display trends (charts, graphs).
- Expand tool capabilities to include other data sources like Reddit or Medium.
- Enable multi-query sessions with saved history.

---

## License
This project is licensed under the **MIT License**.

---

## Contact
For queries or contributions, feel free to reach out:
- **Author**: Stanley Ekene Uzum
- **Email**: stanleyuzum@gmail.com
- **GitHub**: [uzumstanley](https://github.com/uzumstanley)
