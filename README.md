# MCP Learning Path Generator

## Overview

MCP Learning Path Generator is an AI-powered application that creates personalized learning plans based on a user's goal, skill level, and available study time. It uses the YouTube API to find learning resources, generates study schedules, creates notes and quizzes, and stores everything in Google Drive.

## Features

* Personalized learning roadmap
* Automatic study timetable generation
* YouTube playlist creation using YouTube Data API
* AI-generated notes and summaries
* MCQ and quiz generation
* Google Drive integration for storing resources
* Progress tracking dashboard

## Tech Stack

* Python
* FastAPI
* React
* MCP (Model Context Protocol)
* YouTube Data API
* Google Drive API
* OpenAI API
* SQLite/PostgreSQL

## How It Works

1. User enters a learning goal (e.g., Python, React, AI).
2. The system creates a learning roadmap.
3. Relevant YouTube videos are fetched using the YouTube API.
4. A daily/weekly timetable is generated.
5. AI generates notes, summaries, and quizzes.
6. All resources are saved to Google Drive.

## Project Structure

```text
mcp-learning-path-generator/
│
├── backend/
├── frontend/
├── generated_notes/
├── generated_playlists/
├── generated_timetables/
├── README.md
└── requirements.txt
```

## Installation

```bash
git clone https://github.com/yourusername/mcp-learning-path-generator.git

cd mcp-learning-path-generator

pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file and add:

```env
YOUTUBE_API_KEY=your_api_key
GOOGLE_DRIVE_API_KEY=your_api_key
OPENAI_API_KEY=your_api_key
```


## Future Enhancements

* AI chatbot for doubt solving
* Adaptive learning paths
* Certificate generation
* Mobile application
* Learning analytics dashboard

## Author

Soumya Badiger
An AI-powered MCP-based learning assistant that generates personalized learning roadmaps, study timetables, YouTube playlists, notes, and quizzes using YouTube API, Google Drive API, and OpenAI API. It helps learners organize and track their learning journey efficiently.
