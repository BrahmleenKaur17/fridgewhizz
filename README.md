## Hackathon Team Project

This project was developed during a hackathon by a team of three developers, focusing on building a functional prototype within a limited time frame.

Team Members:
- Brahmleen Kaur
- Simran Juneja
- Tanish Vansil


FRIDGEWHIZZ

FridgeWhizz is an intelligent web application that helps users decide what to cook based on the contents of their fridge. By simply uploading a picture of your fridge, the app identifies available ingredients, gathers user preferences, and suggests recipes tailored to taste, skill level, and dietary preferences.

PROJECT OVERVIEW---------------------------------------------------------------------------

FridgeWhizz combines computer vision, AI, and user input to provide personalized recipe recommendations:

Image Processing

Users upload a photo of their fridge.

Ingredients are detected using a BLIP model (with fallback options for robustness).

User Preferences

Users fill a web form specifying:

Skill level (Beginner/Intermediate/Expert)

Dietary choices (Vegetarian, Non-Vegetarian, Vegan, etc.)

Taste preferences (spicy, sweet, savory, etc.)

Recipe Generation

The app sends the detected ingredients and user preferences to the Gemini API.

Gemini generates a personalized recipe suggestion each time.

Taste Feedback

Users can submit a review form with taste feedback.

The system uses feedback to fine-tune future recipe suggestions.

FEATURES-----------------------------------------------------------------------------------

Ingredient detection from fridge images.

Personalized recipe suggestions based on user preferences.

Skill-level adaptation – recipes can be beginner-friendly or advanced.

AI-powered recipe generation via Gemini API.

Fallback mechanism using BLIP for robust image recognition.

Interactive web interface for uploading images and providing taste feedback.
