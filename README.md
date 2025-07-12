# Tour Scraper

This is a simple Python script that scrapes upcoming tour events from a web page and sends an email when a new event is found.

## Features

- Scrapes using CSS selector (`#displaytimer`)
- Stores data in SQLite
- Sends email via Gmail SMTP
- Avoids duplicate events

## Setup

1. Clone the repo
2. Create a `.env` file like this: