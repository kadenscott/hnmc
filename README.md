# HNMC

A Minecraft plugin that adds Hacker News to your server.

# Features

- Let your players waste their time responsibly by providing an in-game UI for Hacker News
- Craftable Hacker News book

### TODO

- Search HN in-game
- Attempt to render website as a book
- Sort types

# Installation

1. Ensure you are running a Paper server running 1.18.1.
2. Add this plugin to your server's `plugins/` folder and restart.
3. Enjoy some Hacker News goodness!

# Usage

HNMC adds a new book called Hacker News. When right-clicked, this book will open up an interface containing the latest
HN posts.

The plugin currently pings the HN API every 10 minutes for the top stories. Only the top stories are available right now.

// **TODO** interface image

To get a Hacker News book, operators can run `/hn get`. Otherwise, the Hacker News book can be crafted using this
recipe:

// **TODO** recipe image

Now you can sit back, relax, and waste time two times as fast.

# Commands

HNMC has a few admin commands to interact with the plugin.

- `/hn` - base command
- `/hn get` - give yourself the HN book
- `/hn give <player>` - give a player the HN book
- `/hn open` - opens the HN menu for yourself
- `/hn open <player>` - opens the HN menu for another player

# Permissions

HNMC comes with a few permissions to control who can access HackerNews.

- `hn.command.use` - access to `/hn` (default: op)
- `hn.craft` - access to the crafting recipe (default: not op)
