
**[▶️ Play SQL Police Detective Game Now!](https://claude.ai/public/artifacts/c90b8392-3372-4c95-aa71-426d28c3466a)**

# SQL Police Detective Game 🚔

An interactive web-based game that teaches SQL through engaging detective missions. Players take on the role of a detective solving crimes using SQL queries to investigate databases and uncover clues.

## 🎮 Game Overview

**SQL Police Detective** is an educational game designed to make learning SQL fun and interactive. Players progress through 5 challenging missions, each requiring different SQL skills to solve crimes and catch criminals.

### 🎯 Learning Objectives

- Master basic SQL SELECT statements
- Learn WHERE clause filtering with multiple conditions
- Practice date range queries with BETWEEN
- Understand ORDER BY for sorting results
- Apply GROUP BY and HAVING for aggregation queries

## 🚀 Features

- **Progressive Difficulty**: 5 missions ranging from basic to advanced SQL concepts
- **Interactive Interface**: Real-time query validation and feedback
- **Detective Theme**: Immersive crime-solving storyline
- **Hint System**: Built-in hints to guide players when stuck
- **Progress Tracking**: Visual progress bar showing mission completion
- **Responsive Design**: Works on desktop and mobile devices

## 🎲 Missions

### Mission 1: The Missing Person
Learn basic SELECT queries to find missing persons in the citizens database.
- **Skills**: SELECT, WHERE with AND conditions
- **Database**: `citizens` table

### Mission 2: The Robbery Investigation
Find suspects using date range queries for a bank robbery case.
- **Skills**: BETWEEN operator, date filtering
- **Database**: `suspects` table

### Mission 3: The Drug Bust
Search for evidence using multiple conditions and date comparisons.
- **Skills**: WHERE with multiple conditions, date comparisons
- **Database**: `evidence` table

### Mission 4: The Serial Case
Investigate connected crimes using sorting and filtering.
- **Skills**: ORDER BY, DESC sorting
- **Database**: `cases` table

### Mission 5: The Final Arrest
Count arrests by officer using aggregation functions.
- **Skills**: GROUP BY, COUNT, HAVING
- **Database**: `arrests` table

## 🛠️ Technical Details

- **Frontend**: Pure HTML5, CSS3, and JavaScript
- **No Dependencies**: Runs entirely in the browser
- **Responsive**: Mobile-friendly design
- **Local Storage**: No backend required

## 🎨 Design Features

- **Dark Police Theme**: Professional law enforcement aesthetic
- **Animated Elements**: Smooth transitions and hover effects
- **Progress Visualization**: Real-time progress tracking
- **Interactive Feedback**: Immediate query validation
- **Badge System**: Police-themed icons and emojis

## 🚀 Getting Started

### Quick Start
1. Download the `sql_police_game.html` file
2. Open it in any modern web browser
3. Start playing immediately - no installation required!

### Running the Game
```bash
# Simply open the HTML file in your browser
# No server setup needed - it runs locally
```

### System Requirements
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- No internet connection required

## 🎯 How to Play

1. **Read the Mission**: Each mission presents a crime scenario
2. **Study the Schema**: Review the database table structure
3. **Write Your Query**: Enter SQL commands in the text area
4. **Execute**: Click "Execute Query" or press Ctrl+Enter
5. **Get Feedback**: Receive immediate success/error messages
6. **Use Hints**: Click "Show Hint" if you need help
7. **Progress**: Complete all 5 missions to become a SQL Detective!

## 🏆 Learning Path

The game is designed with a progressive learning curve:

```
Basic → Intermediate → Advanced
  ↓         ↓           ↓
Mission 1   Mission 3   Mission 5
Mission 2   Mission 4
```

## 📊 Query Examples

### Mission 1 Solution
```sql
SELECT * FROM citizens 
WHERE first_name = 'Sarah' AND last_name = 'Johnson';
```

### Mission 5 Solution
```sql
SELECT officer_name, COUNT(*) 
FROM arrests 
GROUP BY officer_name 
HAVING COUNT(*) > 2;
```

## 🎨 Customization

The game is easily customizable:

- **Add New Missions**: Extend the `gameData.missions` array
- **Modify Styling**: Update CSS variables for different themes
- **Change Database Schema**: Adjust table structures in mission data
- **Add Features**: Extend JavaScript functionality

## 🐛 Troubleshooting

### Common Issues
- **Query Not Accepted**: Check for exact syntax and spelling
- **Case Sensitivity**: The game accepts both upper and lowercase SQL
- **Quotation Marks**: Use single quotes for string values

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 79+

## 🤝 Contributing

Contr
