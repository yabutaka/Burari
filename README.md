# Burari

Burari is an Instagram chatbot that helps you curate your own personal map of places you're interested in exploring across different cities. Message the bot about a place, a vibe, or a city, and it builds out a saved, personalized map you can keep coming back to.

## What it does

- Chat with Burari on Instagram to add places you want to visit
- Ask for recommendations for a city or neighborhood and get suggestions added to your map
- Organize and revisit your personal map of saved places over time

## How it works

Burari runs on Meta's Instagram Messaging API (Graph API). When you message the bot:

1. Your message is received via the Instagram Graph API.
2. The message is processed using OpenAI's API to understand your request and generate relevant suggestions.
3. Place and map data (e.g. search, geocoding, place details) is retrieved via a mapping provider such as Google Maps.
4. The result is sent back to you on Instagram, and relevant details are saved to your personal map.

## Privacy

See [PRIVACY_POLICY.md](./PRIVACY_POLICY.md) or the hosted version at the GitHub Pages link in this repo's description for details on what data is collected and how it's used.

## Status

Burari is in active development.
