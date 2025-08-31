# CrewAI Email Assistant 

This  demonstrates the fundamentals of Agentic AI by creating a simple but powerful Email Assistant Agent using CrewAI and Google Gemini. 

## 🔧 Technologies Used
Python – Core programming language. 
CrewAI – Framework to build agents, tasks, and crews.
Google Gemini API – LLM powering the agents. 
uv – Fast package manager for dependency management.
PyCharm – IDE used for development.
.env file – Securely stores the Gemini API key.

## Email Assistant Agent

The Email Assistant is the first agent built in this project. It is designed to take rough or unprofessional emails and rewrite them into clear, polished, and professional communication.

Role: Communication Expert

Goal: Improve rough emails and make them sound professional.

Backstory: Skilled in business and professional writing.

## 📝 How it Works

A rough email draft is given as input (e.g., full of abbreviations, lowercase text, informal tone).

The Email Assistant Agent processes the email using Gemini as its reasoning engine.

A task is defined for the agent: “Rewrite this draft into a professional and polished version, expanding abbreviations if needed.”

The Crew executes the task and outputs a refined version of the email.

