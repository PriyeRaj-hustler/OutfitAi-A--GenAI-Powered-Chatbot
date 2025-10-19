# AI Fashion Advisor Chatbot

## Overview

This project is an "AI Fashion Advisor," a personal chatbot designed to provide users with outfit advice and style recommendations. A key feature of this application is its integrated feedback pipeline, which allows users to submit feedback on the AI's suggestions, helping to improve future recommendations.

## Key Features

* **Conversational Interface:** Users can ask for fashion advice in natural language (e.g., "What to wear for a date?").
* **AI-Powered Suggestions:** The chatbot provides detailed outfit recommendations, including specific clothing items, accessories, and styling tips.
* **User Feedback Pipeline:** A built-in feedback system on the frontend allows users to submit their thoughts on the AI's suggestions.
* **Feedback Logging:** All user-submitted feedback is automatically logged in a timestamped file (`user_feedback.log`) for review and future model improvements.

## Screenshots

Here you can see the application in action, from the user's request to the feedback being logged.

**1. Main Application Interface & Feedback Submission**
*This image shows the chat interface where the user asks for advice and the feedback panel where they can submit their comments.*
![AI Fashion Advisor Interface](https://github.com/user-attachments/assets/ed93b31f-3bf6-48d7-af77-b6658bb0a8a4)



**2. User Feedback Log**
*This image shows the backend log file (`user_feedback.log`) where the user's feedback is captured and stored.*
![User Feedback Log](https://github.com/user-attachments/assets/b300bb9c-5212-41be-9092-27dd23335683)



## How the Feedback Loop Works

1.  A user asks the **AI Fashion Advisor** for an outfit suggestion.
2.  The AI provides a detailed recommendation.
3.  The user can then use the **Feedback Pipeline** form to submit their thoughts (e.g., "You can suggest Some casual fits too").
4.  Upon submission, the feedback is logged with a timestamp in the `user_feedback.log` file.
5.  This logged data can then be used by developers to analyze user preferences and fine-tune the AI model's responses.

## Future Improvements

* Use the logged feedback to automatically retrain or fine-tune the recommendation model.
* Expand the range of occasions, styles, and body types the AI can cater to.
* Incorporate visual suggestions (images of the recommended outfits) into the chat response.
