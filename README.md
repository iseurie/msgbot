# msgbot
A Python Discord selfbot that stores user messages in individual .csv (comma-separated value) files.

Currently persists a timestamp, Author ID, Guild ID (where applicable), channel ID, and message contents. Private messages are persisted in files corresponding to recipient channel IDs, while guild messages are stored in files corresponding to the guild ID.
