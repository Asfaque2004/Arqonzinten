# Tile Calculator Chatbot Web App

## Overview
This project is a modern, mobile-friendly Tile Calculator web application featuring a conversational chatbot interface. Users can calculate the number of tiles needed for their space, get product recommendations, and export results as a PDF. The app is built with HTML, CSS, and JavaScript, and runs fully in the browser—no backend required.

## Features
- **Conversational Chatbot:** Guides users step-by-step through the tile calculation process.
- **Tile Calculation:** Calculates required tiles and boxes based on area, unit (Sq.Ft/Sq.M), and tile size.
- **Product Recommendations:** Suggests matching and alternative tile products from a sample catalogue.
- **PDF Export:** Download a printable PDF summary of your calculation and recommended products.
- **Responsive Design:** Works great on desktop and mobile devices.
- **Modern UI:** Clean, minimal, and user-friendly interface.

## Setup & Usage
1. **Clone or Download the Repository**
   ```
   git clone <your-repo-url>
   cd <project-folder>
   ```
2. **Open `arqonz.html` in your browser**
   - No build or server required. All logic is in the HTML/JS/CSS files.
3. **How to Use**
   - Follow the chatbot prompts to enter your requirements.
   - After calculation, choose to view matching tiles.
   - Download results as a PDF using the provided button.

## File Structure
- `arqonz.html` — Main web app (chatbot, calculator, product grid)
- `static/css/tile_calculator.css` — Modern responsive styles
- `pdf_template.html` — Printable PDF template for results
- `static/` — Images and icons

## Optional: LLM Backend Integration
- The app is designed to work fully frontend-only, but you can extend it with an AI backend (OpenAI GPT, Gemini, Rasa, etc.) for more advanced conversational flows.
- Ive worked with LLMs before but ive only used them for summarization and other generative purposes where in i already had data. So i wasnt sure how to integrate the LLM for your catalogue. With guidance and more info I'm pretty sure i can do it!
  
## Credits
- UI/UX: Inspired by modern SaaS dashboards and chatbots
- Product images: Sample/stock images for demo purposes
- Chatbot logic: Custom rules-based JavaScript

---

submission by Asfaque Ahamed
