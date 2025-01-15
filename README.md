# ChatBot-NLP
# Food Delivery Chatbot with Dialogflow

This project is an end-to-end solution for creating a chatbot for a food delivery system. It combines Dialogflow for the conversational interface, Python with FastAPI for the backend, and MySQL for database interactions.

## Features
- **Dialogflow Basics**: Learn intents, entities, contexts, and build engaging conversational flows.
- **Backend Development**: Develop a robust backend using Python and FastAPI.
- **Database Integration**: Manage data efficiently with MySQL.
- **End-to-End Functionality**: Connect the chatbot with backend systems and databases for a smooth food delivery experience.

## Tech Stack
- **Dialogflow**: Conversational AI platform.
- **Python**: Backend programming language.
- **FastAPI**: Web framework for building APIs.
- **MySQL**: Relational database.

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/food-delivery-chatbot.git
   cd food-delivery-chatbot
   ```

2. **Set Up the Environment**:
   - Install Python dependencies:
     ```bash
     pip install -r requirements.txt
     ```
   - Configure MySQL database and update connection details in `config.py`.

3. **Dialogflow Setup**:
   - Create a Dialogflow agent and import the intents and entities from the `/dialogflow` folder.

4. **Run the Backend**:
   ```bash
   uvicorn main:app --reload
   ```

5. **Test the Chatbot**:
   - Integrate the Dialogflow agent with the backend and test the complete system.
