# Retrieve player game history

Fetch a list of games played by a player using the `/players/{username}/games` endpoint.

```python
import requests
username = "magnuscarlsen"
response = requests.get(f"https://api.chess.example.com/players/{username}/games?limit=5")
games = response.json()
for game in games:
    print(f"Game {game['game_id']} on {game['date']}: {game['result']}")
```
