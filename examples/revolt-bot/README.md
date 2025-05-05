# Revolt AI Chatbot

A simple AI chatbot for Revolt, powered by the Shapes API. The bot responds with AI-generated messages when tagged in a channel.

## Features

- Responds to mentions/tags using Shapes API
- Uses the eunchae3-0ppi shape for responses
- Handles errors gracefully

## Setup

1. Clone this repository
2. Install dependencies:
   ```
   npm install
   ```
3. Configure your environment variables in the `.env` file:
   ```
   REVOLT_TOKEN=your_revolt_bot_token_here
   ```
   
4. To obtain a Revolt bot token:
   - Go to [revolt.chat](https://revolt.chat)
   - Create a new bot through the developer portal
   - Copy the generated token

## Usage

1. Start the bot:
   ```
   npm start
   ```

2. In any Revolt channel where the bot is present, tag the bot followed by your message:
   ```
   @BotName How are you today?
   ```

## Configuration

The bot is pre-configured to use the Shapes API with the eunchae3-0ppi shape. If you want to modify the API configuration, you can edit the values in the `index.js` file or move them to the `.env` file.

## Troubleshooting

If you encounter issues:
- Ensure your Revolt token is correct
- Check that the bot has permissions to read and send messages
- Verify your internet connection for API access 