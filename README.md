# **Fitness Assistant RAG Application**

The **Fitness Assistant RAG Application** is an AI-powered tool designed to help users achieve their fitness goals by providing personalized guidance. It leverages **Retrieval-Augmented Generation (RAG)** to enhance the functionality of Large Language Models (LLMs) like OpenAI’s GPT, combining AI insights with user-specific data for tailored recommendations.

---

## **Key Features**

1. **Personalized User Profiles**:
   - Users can create and update profiles with details like name, age, weight, height, gender, and activity levels.
   - The app supports tracking fitness goals such as muscle gain, fat loss, and staying active.

2. **Macronutrient Recommendations**:
   - The application calculates personalized daily intake of protein, calories, fat, and carbohydrates based on user profiles and goals.
   - Results are displayed in an easy-to-understand JSON format for clarity and precision.

3. **AI-Driven Assistance**:
   - Users can ask fitness-related questions, and the application provides detailed responses using AI.
   - The system considers user profiles and stored notes to deliver personalized advice.

4. **Notes Management**:
   - Users can add, view, and delete notes related to their fitness journey.
   - These notes help contextualize responses and recommendations provided by the AI.

5. **Modular Flow System**:
   - The app uses **LangFlow** to define flows for handling different functionalities, including macronutrient calculations and Q&A responses.

6. **Interactive Web Interface**:
   - Built using **Streamlit**, the app provides a clean, user-friendly interface for seamless interaction.

---

## **Technology Stack**

1. **Frontend**:
   - **Streamlit**: A lightweight framework for building interactive web applications.

2. **Backend**:
   - **LangFlow**: Manages AI workflows and integrates with OpenAI’s GPT for generating personalized responses.
   - **Python**: Core programming language used for logic, data processing, and API integration.

3. **Database**:
   - **Astra DB (Cassandra)**: Stores user profiles, goals, and notes securely.

4. **Prompts and Flows**:
   - Custom text prompts and JSON-defined flows guide AI responses and processes.

5. **APIs and AI Models**:
   - **OpenAI API**: Powers the LLM functionality for generating fitness recommendations and answering questions.

6. **Environment Management**:
   - Configuration handled using `.env` files for secure storage of API keys and database tokens.
