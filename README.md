# 📰 Daily Headlines

A simple web app for Leon and Caitlin to record the headline of their day.

## About

Every night before bed, we come up with a headline for our day. This app lets us save those headlines and revisit random memories from the past.

## Features

- 📝 **Today Only** - You can only add headlines for today. Miss it and it's gone!
- 🔄 **Random Memories** - See a random past headline on page load, with a refresh button for more
- ☁️ **Cloud Sync** - Stored in GitHub Gist so both of us see the same data
- 📱 **Mobile First** - Optimized for use on phones before bed
- 🌿 **Sage & Forest** - Calming green color scheme

## How It Works

1. Visit the site each day
2. Enter your headline for the day
3. Click Save
4. That's it!

The app automatically:
- Saves to today's date (no picking past dates)
- Syncs to a GitHub Gist
- Shows you a random past headline
- Loads today's headlines if you've already written them (so you can edit)

## Tech Stack

- Pure HTML/CSS/JavaScript
- GitHub Gist for storage
- GitHub Pages for hosting

## Setup

The token is stored locally in your browser's localStorage after first prompt. Both users need to enter it once on their device.

Live at: https://leonlenzo.github.io/headline/
