# API Twitch Game Info
Utility to use with Get User Clips to extract game information from a clip. Requires clip information from [API] Get User Clips. This will use the Twitch Clip ID to retrieve details about the game associated with the clip.

# Requirement
- Firebot 5.57.0-nightly-23.03.22 (JSON Stringify is bugged in 5.57.0)

# Install
+ Download API Twitch Game Info.firebotsetup
+ Import the downloaded file
  + Preset Effect List will be named [API] Get Twitch Game Info by Id (Depends on [API] Get User Clips)

# Usage
Use the custom variable twitchGameData elements to display details.

# Variables
+ twitchGamesJson: List of game details
+ twitchGamesData: Array of game details
  + Refer to Twitch API documentation for field names
  + boxArtUrl: Extracted URL of the game art, for use in displaying game icon

# References
+ https://dev.twitch.tv/docs/api/reference/#get-games
