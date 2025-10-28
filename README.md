#cooknetic_Ai
---

Cookentic AI – Your AI Kitchen Assistant

Cookentic AI is an all-in-one smart cooking assistant that uses AI to scan fridge images, detect ingredients, and generate delicious recipes. It also works in reverse: input a recipe, and it tells you what ingredients you’ll need — all in a single, offline-capable file with no external API dependencies.


---

Features

Fridge Scanner – Upload or capture a photo of your ingredients and get recipe suggestions.

Recipe Analyzer – Paste any recipe text, and get a list of required ingredients.

Offline & API-Free – Everything runs client-side using TensorFlow.js — fast, secure, and private.

Minimal UI – Clean, responsive TailwindCSS interface designed for ease-of-use.

One-file Deployment – Just one HTML file to copy and run — no setup, no backend.



---

Getting Started

1. Clone or download the repository.


2. Open index.html in your browser.


3. Upload an image of food OR paste a recipe text.


4. Click the buttons to scan or generate ingredients/recipes.




---

Technology Stack

HTML5 + TailwindCSS (UI)

JavaScript (Vanilla)

TensorFlow.js + COCO-SSD (Image recognition)

Custom logic (for text-to-ingredient parsing & recipe generation)



---

How It Works

1. Scan Fridge Image

Uses TensorFlow’s COCO-SSD model to detect visible food items.

Filters non-food items using a custom whitelist.

Displays ingredients and auto-generates a sample recipe.


2. Recipe to Ingredient

Accepts raw recipe instructions.

Uses simple NLP parsing to extract possible ingredients mentioned in the text.



---

Use Cases

Quick meal ideas from random fridge items.

Reverse engineer a recipe to make a shopping list.

Camping, travel, or low-connectivity cooking.

Educational tool for beginner cooks.



---

Business Model

Freemium App: Basic features are free; premium version adds:

Nutrition data

Grocery list generation

Smart meal planner


Partnerships with grocery delivery, smart kitchens, or diet apps.



---

Unique Value Proposition

Cookentic AI is private, fast, and ready — designed for real-world kitchens, not cloud dependencies
