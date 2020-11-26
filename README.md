# football-epl-team-comp-19

Dataset of Team Composition from English Premier League Season 2019-2020

Structure :
```
[
  {
    "events": 
      {
      "7": {"type": "own_goal", "players": ["Grant Hanley", "Own Goal"]}, 
      "19": {"type": "goal", "players": ["Mohamed Salah", " Roberto Firmino"]}, 
      "28": {"type": "goal", "players": ["Virgil van Dijk", " Mohamed Salah"]}, 
      ... },
    
    "composition": 
    { 
      "home": {"player_0": {"name": "Roberto Firmino", "min": 85}, 
               "player_1": {"name": "James Milner", "min": 5},
               ...
               "player_9": {"name": "Virgil van Dijk", "min": 90}
               },
               
      "away": {"player_0": {"name": "Teemu Pukki", "min": 82}, 
               "player_1": {"name": "Josip Drmić", "min": 8}, 
               ...
               }
               
  }
  
  ...
] ```
