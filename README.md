 MedBot-AI 

A Rule-Based Medical Chatbot with GUI using Python and UCS Algorithm

Project Overview
MedBot-AI is a simple medical chatbot designed to assist users by identifying possible diseases based on the symptoms they describe. The system uses a rule-based approach combined with the Uniform Cost Search (UCS) algorithm to determine the most likely disease and suggest basic treatments.

The chatbot features an interactive GUI built using Tkinter, making it user-friendly and suitable for demonstration purposes in academic and learning environments.

Objectives
 -To simulate a basic medical consultation chatbot
 -To apply AI search algorithms (UCS) in a real-world inspired problem
 -To design a simple yet functional desktop-based chatbot UI
 -To demonstrate symptom-based disease matching

Technologies Used
 -Python
 -Tkinter (GUI)
 -Uniform Cost Search (UCS)
 -Heap Queue (heapq)
 -CSV-based sample dataset

System Architecture
User
  │
  ▼
Tkinter GUI (Chat Interface)
  │
  ▼
Input Processing & Session Symptom Tracker
  │
  ▼
Uniform Cost Search (UCS) Algorithm
  │
  ▼
Disease-Symptom Knowledge Base
  │
  ▼
Diagnosis & Treatment Recommendation

Working Principle
1. The user enters symptoms in natural language through the GUI.
2. Symptoms are accumulated during the session.
3. The UCS algorithm calculates the cost based on unmatched symptoms.
4. The disease with the minimum cost is selected as the best match.
5. The chatbot displays:
    Possible disease
    Basic treatment suggestions
6. The chatbot can also assess condition severity based on symptom duration.

Dataset Information
The project includes a small sample dataset for demonstration.
Sample Dataset Structure. A hard-coded knowledge base

| Disease        | Symptoms               | Treatment                 |
| -- | - | - |
| Flu            | fever, headache, cough | Paracetamol, rest         |
| Migraine       | headache, nausea       | Pain relievers, dark room |
| Cold           | sneezing, cough        | Warm fluids               |
| Food Poisoning | vomiting, diarrhea     | Hydration                 |

How to Run the Project
-Clone the repository
-bash
-git clone https://github.com/NiharikaKulkarni/MedBot-AI.git
-cd MedBot-AI
-Run the chatbot

Key Features
-Interactive GUI-based chatbot
 -Symptom session tracking
 -UCS-based disease matching
 -Simple severity analysis
 -Beginner-friendly AI project

Future Enhancements
 -Integration with real medical datasets
 -NLP-based symptom extraction
 -Machine Learning–based diagnosis
 -Web-based interface
 -RAG-based medical assistant

Author
Niharika Kulkarni

**Disclaimer**
This chatbot is strictly for educational and academic purposes.
Always consult a certified medical professional for real medical concerns.
