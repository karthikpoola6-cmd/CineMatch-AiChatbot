# CineMatch - Movie Recommendation Chatbot

A movie recommendation chatbot built with JavaScript. Ask for movies by genre, mood, or find similar films to ones you love.

## Live Demo

Check it out here: https://karthikpoola6-cmd.github.io/CineMatch-AiChatbot

Note: The live site uses a curated database of movies. AI features work when running locally with your own API key.

## What It Does

- Search by genre (sci-fi, horror, comedy, action, romance, drama, animated)
- Find movies similar to ones you already like ("movies like Interstellar")
- Filter by time period ("sci-fi movies after 2007")
- Get 5-10 movie recommendations with descriptions
- Clean, modern purple and gold interface

## How to Use

Just type what you're looking for:
- "sci-fi movies"
- "something funny"
- "movies like Inception"
- "horror after 2010"
- "I want to cry"

The chatbot will give you movie recommendations with genre, year, and why each movie matches your request.

## Tech Stack

- HTML, CSS, JavaScript
- Claude AI API (for local development)
- GitHub Pages for hosting
- 100+ movie database for live site

## Features

- Natural language understanding (recognizes lots of different ways to ask)
- Genre filtering
- Time period filtering  
- Movie similarity matching
- Responsive design (works on phone, tablet, computer)
- Fast responses

## Running Locally with AI

If you want to test the AI features on your computer:

1. Get a API key from console.anthropic.com 
2. Download the files from this repo
3. Open terminal in the folder
4. Run: `python -m http.server 8000`
5. Go to: http://localhost:8000
6. Enter your API key when prompted

The AI mode gives more conversational responses and can understand complex requests better.

## How It Works

The chatbot looks for keywords in your message (like "sci-fi", "horror", movie titles, etc.) and matches them to a database of movies. Each movie has a title, genre, year, and reason why it's good.

When you ask "movies like Interstellar", it finds Interstellar in the database and shows you similar space/sci-fi films.

## Database

The basic mode includes over 100 curated films across all major genres, plus specific "similar movies" lists for popular films like Interstellar, Inception, The Godfather, Parasite, and Shawshank Redemption.

## Built By

Karthik Poola

GitHub: https://github.com/karthikpoola6-cmd

Project Link: https://github.com/karthikpoola6-cmd/CineMatch-AiChatbot
