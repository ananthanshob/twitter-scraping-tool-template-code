# Twitter Scraping Tool

This tool uses the Twitter API to search for Twitter profiles based on specific keywords and filters them by follower count. Results are saved to a CSV file.

## Features
- Authenticate with the Twitter API.
- Search for users based on keywords in tweets.
- Filter users by follower count.
- Save filtered profiles to a CSV file.

## Setup
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Replace `YOUR_BEARER_TOKEN_HERE` in `twitter_scraper.py` with your actual Twitter API bearer token.
4. Modify the `keywords` list in `main()` to search for specific terms.

## Usage
Run the script with:
```bash
python twitter_scraper.py
