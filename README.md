# Nyx Browser - README

Nyx Browser is a Python-based AI-powered web browser that simplifies information retrieval and summarization using web scraping, asynchronous tasks, and AI-driven summarization. This browser can search Google for links, scrape content, fetch images, and summarize the information using the LLaMA language model by Ollama. It also includes a PyQt5 interface.

## Table of Contents

1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Installation](#installation)
4. [Running the Application](#running-the-application)
5. [Usage](#usage)
6. [Project Structure](#project-structure)
7. [Configuration](#configuration)
8. [Notes](#notes)
9. [License](#license)

## Features

- **Google Search & Web Scraping:** Searches for a user-specified query on Google, fetches the top links, and scrapes content from them.
- **Image Retrieval:** Fetches images related to the search query from Google Images.
- **AI-Powered Summarization:** Summarizes scraped content with instructions based on user queries, using the LLaMA model from Ollama.
- **Frontend with Flask & PyQt5:** Serves a web-based frontend with Flask, also accessible through a PyQt5 GUI.
- **Live Progress & Error Handling:** Displays real-time progress for ongoing tasks with toast notifications and a progress bar.

## Technologies Used

- **Python (Flask, aiohttp, asyncio, threading):** Backend for asynchronous web scraping and task management.
- **BeautifulSoup & aiohttp:** Web scraping tools for parsing and fetching data from search results.
- **LangChain & Ollama:** Framework for creating prompts and interacting with the LLaMA language model.
- **PyQt5:** For a GUI interface.
- **HTML/CSS & JavaScript:** Frontend styling and functionality.

## Installation

### Prerequisites

- **Python 3.7+** is required.
- **Ollama and LLaMA 3.2** need to be installed and properly configured on your system.

### Installing Dependencies

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/nyx-browser.git
   cd nyx-browser
