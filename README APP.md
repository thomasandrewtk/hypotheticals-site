# Hypotheticals: The Game

A SwiftUI party game where players debate outrageous scenarios in a game show format. Teams face off in timed debates, arguing for or against bizarre hypothetical situations, with designated judges deciding the winners.

## What's New
- **Streamlined Gameplay**: Faster-paced rounds with focused arguments
- **Simplified Debate Structure**: Clear, concise format for better engagement
- **Enhanced Flow**: Smoother transitions between phases

## Game Overview

**Hypotheticals** is an engaging party game that combines quick thinking, persuasive skills, and humor. Players are divided into teams to debate thought-provoking scenarios, with app-designated "Hotshots" arguing their case as either an "Optimist" or "Skeptic". One or more "Deciders" judge the most persuasive argument, leading teams to victory through wit and charm.

### Core Concept

Each round centers on a "Hypothetical" - a unique scenario designed to spark debate. Each hypothetical consists of:
- **The Good Thing:** A desirable event, power, or situation (e.g., "You can talk to squirrels...")
- **The Bad Thing:** A significant downside or ironic consequence (e.g., "...but they only ever offer terrible financial advice.")

Players must weigh these elements and argue their team's assigned stance on whether the premise is "worth" the catch.

## Features

### Game Mechanics
- **Team-based Gameplay:** Players are divided into two teams with themed names
- **Dynamic Roles:** 
  - **Hotshots:** Team members who present arguments
  - **Deciders:** Impartial judges who determine round winners
- **Automated Debate Flow:** Structured rounds with timed phases
- **Random Pack Option:** Mix hypotheticals from different packs each round
- **No Repeat Hypotheticals:** Tracking system ensures scenarios don't repeat in a game

### UI/UX ("Game Show Glam" Theme)
- **Dark Mode Excellence:** Polished dark theme with vibrant accents
- **Intuitive Navigation:**
  - Back navigation throughout game flow with standard iOS chevron design
  - Consistent back button styling in spotlight yellow
  - "Forget Someone?" option to return to player entry
  - Settings access via gear icon on welcome screen
- **Game Customization:**
  - Adjustable argument timer (10-60 seconds)
  - Customizable victory target (3-15 points)
  - Settings persist between game sessions
- **Color Palette:**
  - Primary: "Spotlight Yellow" for highlights and key elements
  - Team Colors: "Game Show Green" (Optimists) and "Game Show Red" (Skeptics)
  - Accents: Electric Blue, Playful Purple
  - Backgrounds: Dark Background Primary, Dark Card Background
- **Typography:** SF Rounded font family with consistent hierarchical styles
- **Styled Components:**
  - Game Cards with spotlight yellow borders
  - Dynamic Timer Banner with phase-specific colors
  - Focused Action Cards for current speakers
  - SF Symbol Background Pattern

### Game Flow
1. **Welcome & Setup**
   - Quick access to game settings via gear icon
   - Pack Selection (including "Random" option)
     - Back navigation to welcome screen
   - Player Entry (3-10 players)
     - Back navigation to pack selection
     - Swipe-to-delete player management
   - Automatic Role Assignment
     - "Forget Someone?" option to add more players
   - Team Formation with themed names

2. **Round Structure**
   - Reading Phase (10 seconds)
   - Optimist Argument (customizable duration)
   - Intermission (5 seconds)
   - Skeptic Argument (customizable duration)
   - Decision Phase

3. **Scoring & Progress**
   - Points awarded by Deciders
   - Individual "Successful Pleads" tracking
   - First team to customizable target score wins
   - "Most Persuasive Hotshot" recognition

## Content Packs

The game includes several themed packs:
1. **Silly Starters:** Absurd scenarios to get everyone laughing
2. **Deep Dilemmas:** Thought-provoking choices with tricky consequences
3. **Superpower Snags:** Amazing abilities with even more amazing downsides
4. **Everyday Oddities:** Slightly strange twists on normal life

Each pack includes:
- Unique hypothetical scenarios
- Themed team name pairs
- Difficulty rating (Easy, Medium, Hard)

## Technical Features

### Error Handling
- No More Hypotheticals Error detection and user feedback
- Graceful handling of edge cases
- Clear error messages and recovery options

### State Management
- Robust game session tracking
- Persistent score and progress monitoring
- Clean phase transitions

### Performance
- Efficient timer management
- Smooth animations and transitions
- Responsive UI updates

## Future Enhancements

Planned features for future updates:
- All-Time Individual Leaderboard
- Customizable Game Settings (timers, target score)
- Additional Hypothetical Packs
- User-Generated Content Support
- Sound Effects & Music
- Advanced Statistics Tracking
- Alternative Game Modes

## Contributing

Found a bug or have a suggestion? Please report it to help us improve! The game is actively maintained and enhanced based on player feedback.

## Credits

Developed using SwiftUI. Special thanks to all players who've helped test and refine the game concept.

---

*"Think Twice, Argue Once, Win Big!"* 

<form action="https://formsubmit.co/your@email.com" method="POST">
    <input type="email" name="email" placeholder="Enter your email" required>
    <button type="submit">Join waitlist</button>
    <input type="hidden" name="_next" value="https://yoursite.com/thanks.html">
</form> 