# Bluesky WebSocket Projects

This repository contains web applications that interact with Bluesky's WebSocket firehose API.

## Projects

### 1. BlueskyFM

A real-time music discovery tool that monitors Bluesky's network for Spotify links. The application creates a live feed of tracks, albums, and playlists being shared across the Bluesky social network.

**Features:**

- Real-time monitoring of Bluesky posts
- Automatic detection of Spotify links (tracks, albums, playlists, and artists)
- Embedded Spotify players for instant playback
- Live statistics tracking (posts scanned and Spotify links found)
- Responsive design with a Spotify-inspired dark theme
- Maximum of 50 most recent music shares displayed
- Automatic cleanup of older entries

### 2. Bluesky TV

A real-time video discovery platform that monitors Bluesky's network for YouTube links, creating an instant feed of videos being shared and discussed.

**Features:**

- Live monitoring of Bluesky's firehose for YouTube links
- Automatic YouTube video embedding
- Video availability verification before display
- Maximum of 50 most recent video shares
- Real-time statistics (posts scanned and videos found)
- Responsive grid layout for optimal viewing
- YouTube-inspired dark theme
- Links to original Bluesky posts
- Automatic cleanup of older entries
- Manual connect/disconnect controls

## Technical Details

These applications utilize Bluesky's WebSocket endpoint at `wss://jetstream2.us-east.bsky.network/subscribe` to monitor the `app.bsky.feed.post` collection in real-time.

## Credits

BlueskyFM was built by Si Quick with inspiration from Simon Willison.
