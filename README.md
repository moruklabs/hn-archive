
# Product Hunt RSS Archive

This project archives daily RSS feeds from Product Hunt, categorizing them by date and topic. It aims to provide a historical record of Product Hunt's daily top products, making it easier to analyze trends and specific product launches over time.

## Project Structure

- `main.py`: The main script responsible for fetching, parsing, and storing RSS feeds.
- `config.json`: Configuration file for RSS feed sources and output directories.
- `rss/`: Directory where the archived RSS feeds are stored, organized by date and topic.
- `AGENTS.md`: Guidelines and checks for contributors and automated agents.
- `setup.sh`: Script for initial project setup.
- `requirements.txt`: Python dependencies.

## Setup and Usage

1. **Installation:**
   ```bash
   ./setup.sh
   ```

2. **Running the archiver:**
   ```bash
   python main.py
   ```

## Contribution

See `AGENTS.md` for guidelines on contributing to this project.
