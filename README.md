# RSS Reader

## Description
This program reads an RSS 2.0 feed provided by the user, processes the XML data, and generates a formatted HTML web page with links to the news items. It demonstrates XML processing, RSS technology, and Java-based HTML generation.

## Objectives
- Familiarity with processing XML using `XMLTree`.
- Practice using `while` loops and static methods.
- Exposure to RSS feed structures and web content syndication.

## Features
1. **Input**:
   - RSS 2.0 feed URL provided by the user.
   - Name of the output HTML file.

2. **Output**:
   - HTML page including:
     - Page title based on the RSS channel's title or "Empty Title" if not available.
     - Channel description or "No description" if not available.
     - A table with the following columns:
       - Publication date (or "No date available").
       - Source linked to its URL (or "No source available").
       - News item title or description linked to the news item URL (or "No title available").

3. **Error Handling**:
   - Ensures the RSS feed is valid and adheres to the 2.0 specification.
   - Handles missing or empty tags gracefully.

## Technologies Used
- Java
- `XMLTree` library for XML processing
- RSS 2.0 specification

## How to Run
1. Clone the repository:
   ```bash
   git clone [repository URL]
