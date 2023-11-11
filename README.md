# Secret Santa Matcher

Generate random matches for a game of Secret Santa.

### [Try demo](https://santas.surge.sh)

## What it does

1. Type your list of participants (saved to local storage)
2. Add exclusions in brackets eg. Bob (Jane) - Bob won't match with Jane
3. Generates a list of matches, with the receiver encoded as a base64 string. Not the most secure format but enough to obfuscate the name for a casual game
4. Provides a link to each participant where they can reveal their match but decoding the base64 string.
