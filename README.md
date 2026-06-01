# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date: 29/05/2026
# Register no.212223230252

# Aim

To develop a prompt-based application using OpenAI ChatGPT that helps users manage daily tasks, schedule reminders, provide wellness tips, and answer general queries using natural language interaction.

# Objective

The objective of this experiment is to:

Design a personal productivity assistant using prompt engineering.
Create prompts for multiple assistant functionalities.
Simulate user interaction using natural language.
Demonstrate adaptive and intelligent responses using LLMs.
Understand the practical applications of Generative AI in daily productivity management.
AI Tool Used
ChatGPT by OpenAI

## Problem Statement

Design a personal productivity assistant that can:

Manage daily tasks.
Schedule reminders.
Suggest wellness tips.
Answer general queries.
Adapt to user preferences over time.

The assistant should interact naturally and intelligently with users.

Core Requirements of the Productivity Assistant
1. Daily Task Management
Add tasks using natural language.
Organize tasks by:
Priority
Deadline
Completion status
Provide summaries of pending work.
2. Smart Scheduling
Set reminders automatically.
Detect scheduling conflicts.
Suggest free time slots.
3. Wellness Recommendations
Suggest:
Water intake reminders
Exercise breaks
Sleep improvement tips
Screen-time reduction
4. General Query Handling
Answer productivity-related questions.
Provide study tips and time-management advice.
5. Adaptive Memory (Optional)
Store user preferences.
Improve suggestions based on past interactions.
Prompt Engineering Design
Basic Prompt
Act as a personal productivity assistant.
Help manage daily tasks, reminders, wellness tips, and answer user questions.
Respond politely and clearly.
 
##Advanced Prompt

You are an intelligent personal productivity assistant.

Your responsibilities:
1. Manage tasks and reminders.
2. Organize schedules based on priority and deadlines.
3. Suggest personalized wellness tips.
4. Answer general productivity questions.
5. Adapt responses based on previous user preferences.

# Interaction Rules:
- Use friendly natural language.
- Give concise and organized responses.
- Detect scheduling conflicts.
- Encourage healthy habits and work-life balance.

Example:
User: "Remind me to submit my assignment tomorrow at 5 PM."
Assistant:
"Reminder added: Submit assignment tomorrow at 5 PM."

## Procedure
Step 1: Define Requirements

The main features of the productivity assistant were identified:

Task management
Scheduling
Wellness support
Natural language interaction
Step 2: Construct Prompts

Different prompts were designed for:

Task management
Reminder scheduling
Wellness recommendations
User queries
Step 3: Simulate User Interaction

Natural language conversations were simulated using ChatGPT.

Step 4: Collect User Inputs

The assistant accepted:

Task details
Schedule requests
Wellness preferences
Step 5: Adapt Responses

The assistant adjusted responses according to:

User habits
Frequently used reminders
Preferred response style
Sample Interactions and Outputs
1. Daily Task Manager
User Input
Remind me to call my friend at 6 PM.
Assistant Output
Reminder added successfully.
Task: Call my friend
Time: 6:00 PM
Priority: Normal
User Input
Show my pending tasks.
Assistant Output
Pending Tasks:
1. Call my friend – 6 PM
2. Complete AI assignment – Tomorrow 10 AM
3. Attend project meeting – Friday 2 PM
2. Smart Scheduler
User Input
Schedule a study session from 5 PM to 7 PM.
Assistant Output
Study session scheduled from 5 PM to 7 PM.

Warning:
You already have a reminder at 6 PM.
Suggested free slot:
7:30 PM to 9 PM
3. Wellness Tips Generator
User Input
Give me a wellness tip.
Assistant Output
Wellness Tip of the Day:
Take a 5-minute break after every 45 minutes of screen time to reduce eye strain and improve focus.
Adaptive Wellness Suggestion
User Input
I prefer indoor exercises.
Assistant Output
Preference saved.

Suggested Indoor Activities:
- Yoga
- Stretching
- Bodyweight exercises
- Meditation sessions
4. General Query Handling
User Input
How can I improve concentration while studying?
Assistant Output
Tips to Improve Concentration:
1. Use the Pomodoro Technique.
2. Study in a distraction-free environment.
3. Keep your phone away during study sessions.
4. Take short breaks regularly.
5. Stay hydrated and sleep properly.
Python Prototype (Simple Command-Line Version)
tasks = []

print("=== Personal Productivity Assistant ===")

while True:

    user_input = input("You: ")

    if "remind me" in user_input.lower():
        tasks.append(user_input)
        print("Assistant: Reminder added successfully.")

    elif "show tasks" in user_input.lower():
        print("Assistant: Your Tasks:")
        for task in tasks:
            print("-", task)

    elif "wellness tip" in user_input.lower():
        print("Assistant: Drink enough water and take regular screen breaks.")

    elif "exit" in user_input.lower():
        print("Assistant: Goodbye!")
        break

    else:
        print("Assistant: I can help manage tasks and reminders.")
# Features Achieved
Feature	Status
Natural Language Task Input	Implemented
Reminder Scheduling	Implemented
Wellness Suggestions	Implemented
General Query Support	Implemented
Adaptive Preferences	Partially Implemented
Command-Line Simulation	Implemented

# Observations
Structured prompts improved response quality significantly.
Natural language interaction made the assistant more user-friendly.
Prompt engineering helped guide the AI toward specific assistant behavior.
Adaptive prompts created more personalized interactions.
ChatGPT effectively simulated a productivity assistant with minimal coding.

Advantages of the System
Easy task management
Improved productivity
Personalized wellness support
User-friendly interaction
AI-driven automation

## Applications

This system can be used in:

Student productivity management
Office scheduling assistants
Personal wellness tracking
Academic planning
Daily reminder systems

## Result

The experiment successfully demonstrated the creation of a prompt-based personal productivity assistant using OpenAI ChatGPT.

The system was able to:

Manage tasks using natural language.
Schedule reminders intelligently.
Provide wellness recommendations.
Answer user queries interactively.
Adapt partially to user preferences.

Students gained practical experience in:

Prompt engineering
AI-assisted application design
Conversational AI systems
Generative AI integration for real-life applications

## Conclusion

This experiment demonstrated how prompt engineering and Generative AI can be used to create intelligent productivity assistants. 
By designing structured prompts and simulating natural interaction, the assistant successfully managed tasks, reminders, wellness tips, and general user queries.

The experiment highlighted the flexibility and usefulness of AI-powered assistants in improving everyday productivity and demonstrated the importance of carefully designed prompts for achieving accurate and context-aware AI responses.
