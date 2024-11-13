# MAEVE

## Table of Contents
1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Objective](#objective)
4. [Solution Overview](#solution-overview)
5. [Technology Stack](#technology-stack)
6. [Core Features](#core-features)
7. [System Architecture](#system-architecture)
8. [User Interaction Flow](#user-interaction-flow)
9. [Key Functionalities](#key-functionalities)
10. [Demo Video](#demo-video)
11. [Video Description](#video-description)
12. [Conclusion](#conclusion)
13. [Future Improvement](#future-improvements)


## Introduction
This project is a women-centered mental health support platform designed to provide a safe, confidential space for navigating challenges related to mental health, workplace discrimination, harassment, and emotional well-being. Powered by Gemini AI, the platform offers two key features: an AI-driven chatbot that delivers personalized, context-aware support and guidance, and an anonymous human-to-human interaction option that allows users to seek help or provide support through private conversations. Together, these features create a secure, empathetic environment where women can connect, find understanding, and foster resilience.
## Problem Statement
In today's world, women often face unique challenges such as gender bias, discrimination, and a lack of support,etc. These challenges can lead to stress, anxiety, and burnout. Despite the growing recognition of mental health, there is a lack of accessible mental health resources that cater specifically to women’s needs.

## Objective
The objective of this project is to create a chatbot that can assist women by providing mental health support tailored to their challenges. The chatbot:
- Offers personalized responses based on user inputs.
- Provide resources and advice for managing stress and emotional well-being.
- Maintain user privacy and confidentiality.
## Solution Overview
The chatbot will use Gemini AI to understand user inputs and generate contextually appropriate responses. It will be accessible through a simple user interface web application, making it easily available to users at any time.

## Technology Stack
- *Backend*: Node.js, Express
- *Frontend*: HTML,CSS
- *Text processing and response*:Gemini AI
- *Database*: MongoDB (for storing user interaction data, if required)
- *Authentication*: JWT, OAuth
- *Hosting*: Heroku, AWS, or Google Cloud Platform

## Core Features
- *Personalized Conversations*: Tailored responses based on the user's inputs.
- *Real-time Support*: Immediate help and advice for challenges.
- *Confidentiality*: Secure data storage and interaction handling.


## System Architecture
The chatbot system architecture consists of:
- *Frontend*: Web interface where users interact with the chatbot.
- *Backend*: Handles user inputs, processes through Gemini AI, and sends appropriate responses.
- *Database*: Stores necessary user interaction data, such as session history.

## User Interaction Flow
 Chatbot:
1. The user opens the chatbot interface and gets authenticated before they can initiate a conversation.
2. The chatbot asks questions related to their emotional state or challenges.
3. Based on the user's responses, the chatbot offers personalized advice and resources.
4. The user can choose to continue the conversation or end the session.
## Key Functionalities
- *Text Analysis*: The bot analyzes the user's input to detect emotional tone and context.
- *Personalized Recommendations*: Based on the detected context, it suggests tailored resources and coping mechanisms.
- *Privacy Protection*: Ensures that all user data is stored securely and anonymously.
- *Feedback Mechanism*: Users can provide feedback on the chatbot’s responses for continuous improvement.

  
# Human-to-Human interaction:
This component allows women facing emotional or mental health challenges to connect with others  who may understand their experiences (in a private, anonymous environment).So here the users can do two things: 
-Seek help from others
-Offer support themselves
	
# Asking for help:
-*Posting a Query*: Users can post their issues or questions publicly for other members to see. This query will be visible to all, allowing potential helpers to find and respond to those they feel they can support.
-*Selecting a Helper*: Once a user posts a query, they will receive notifications when other users express interest in helping. The user seeking help can then review these notifications and select one person to initiate a private, one-on-one conversation for more personalized support.

# Helper view:
-*Viewing Queries*: Helpers have access to a list of queries posted by users who need support. They can browse these and find queries they feel equipped or inspired to respond to.
-*Expressing Interest*: If a helper wants to offer assistance, they can click "I want to help" on a specific query. Before sending this request, helpers will provide a brief description explaining why they’re interested—such as having similar experiences or specific ways they believe they can assist.
	• Private Conversations: When the user who posted the query accepts a helper’s offer, both users are directed to a private conversation, creating a safe space for open and empathetic dialogue.

This human-chat option encourages mutual support and sharing within the community, empowering users to connect, help each other, and find understanding in a secure, respectful environment.


## Demo Video
[Link to Demo Video](#) 

## Video Description
This video demonstrates how the platform works, including how the chatbot interacts with the user, provides personalized support, and offers resources. It also showcases the interface of the User-User interactions.

## Conclusion
The Personalized Mental Health Chatbot for Women Facing Challenges aims to make mental health support more accessible and personalized for women. By using Gemini AI, it can offer timely assistance, reduce stress, and promote overall well-being. This chatbot serves as an important tool in addressing the mental health needs of women.The other aspect of women's mental health in this applictaion is connecting women who are going through similar life experiences. This platform provides a safe space for women to express, heal, and help themselves and others.

## Future Improvement
- *Expanding Language Support*: Incorporating multilingual support for a wider audience.
- *Integration with HR Systems*: To provide further tailored advice based on workplace-specific challenges.
- *Emotional Intelligence Enhancements*: Using Gemini AI to better understand and respond to complex emotional cues.
- *Addition of voice support*: Using speech processing to make the chatbot more accessible and interactive.
- *Connecting women in workspaces*:Connecting women in the same workplace as a support system.
