# league-customs

When you have more than 5 people and can't play ARAM, you may want to find a way to make a 3v3 customs game. In this case, it can be chaotic to try to alternate teams. This web application provides a simple solution for randomly splitting players into fair teams with League of Legends champion assignments.

## Features

🎮 **Team Randomizer**: Enter player names and get randomly assigned to Blue/Red sides  
⚖️ **Fair Distribution**: Automatically creates balanced 3v3 teams  
🏆 **Champion Assignment**: Randomly assigns League of Legends champions to players  
🔄 **Side-Based Teams**: Organizes teams into Blue Side vs Red Side (like in actual LoL)  
👥 **Minimum 6 Players**: Enforces the requirement for meaningful team games  
🔄 **Substitute Handling**: Extra players become substitutes with champion assignments  
📱 **Responsive Design**: Works on desktop and mobile devices  
🚀 **Auto-Deployment**: Automatically deployed via GitHub Actions to GitHub Pages  

## How to Use

1. Visit the deployed application at [GitHub Pages URL]
2. Enter player names one by one using the input field
3. Toggle champion assignment on/off as desired
4. Click "Add Player" or press Enter to add each player
5. Once you have 6 or more players, click "Randomize Teams"
6. Teams will be randomly generated and assigned to Blue/Red sides
7. Champions will be randomly assigned to each player (if enabled)
8. Any extra players will be listed as substitutes

## Example Output

- **6 players**: 1 Blue Side team (3 players) vs 1 Red Side team (3 players)
- **8 players**: 2 Blue Side teams vs 2 Red Side teams + 2 substitutes  
- **9 players**: 3 teams alternating Blue/Red sides

## Champion Database

The application includes a comprehensive database of 160+ League of Legends champions, ensuring no duplicate assignments within the same game session.

## Requirements

- Minimum 6 players (for 3v3 teams)
- Modern web browser with JavaScript enabled
- No server or installation required - just open the HTML file!

## Technical Details

- Pure HTML/CSS/JavaScript (no frameworks)
- Client-side only (no data sent to servers)
- Responsive design for mobile and desktop
- Input validation and error handling
