# Wellness Tracker - Complete Features

## 🎯 Overview

A comprehensive wellness application with emotional support chatbot, goal tracking, progress monitoring, and brain games.

## ✨ Key Features

### 1. **Multi-Page Navigation**

- **Home**: Emotional Support Chatbot
- **Goals**: Set and track wellness goals
- **Tracker**: View progress charts and game statistics
- **Games**: Play various brain games

### 2. **Responsive Sidebar Navigation**

- **Desktop**: Click the ☰ button in the header to toggle sidebar
- **Mobile**: Automatically collapsible with slide-in effect
- Smooth transitions and professional design

### 3. **Mood-Based UI Customization**

- Select mood with emojis: 😊 Happy | 😢 Sad | 😠 Angry | 😰 Anxious | 😐 Neutral
- Entire website theme changes based on mood
- Beautiful gradient backgrounds for each mood
- All components reflect the selected mood

### 4. **AI-Powered Emotional Support Chatbot**

- **Advanced LLM Integration**: Uses OpenAI's GPT-4o mini
- **Mood-Aware Responses**: AI considers your emotional state
- **Reflective Support**: Genuine empathetic conversations
- **Fallback Mode**: Works without API key using scripted responses
- **Setup**: Enter your OpenAI API key to enable advanced AI

### 5. **Goal Management**

- Set personal wellness goals
- Track completion status
- Delete unwanted goals
- Visual strikethrough for completed goals
- All data persists in localStorage

### 6. **Advanced Brain Games**

#### 🎯 **Tic Tac Toe**

- Play vs AI (default mode with smart AI)
- Play vs Human (local 2-player)
- Mode selector buttons
- Clear game results display
- Auto-reset after game end

#### 🧠 **Memory Game**

- 16 cards with matching pairs
- Tracks moves and time
- Real-time statistics display
- Completes when all pairs are matched
- Victory screen with performance metrics

#### 🔢 **Sudoku**

- Auto-generated puzzles
- Editable cells for user input
- Pre-filled cells are locked
- Interactive gameplay
- Future solve and hint features

#### 🔤 **Word Search**

- 10x10 grid
- Hidden programming-related words
- Visible word list to find
- New puzzle generation
- Various difficulty words

### 7. **Progress Tracking & Statistics**

- **Goals Chart**: Line chart showing daily goal completions
- **Game Statistics**: Bar chart showing games played by type
- Auto-updating charts (every 5 seconds)
- Real-time performance monitoring
- Historical data tracking

### 8. **Game Card Selection UI**

- Beautiful card-based interface
- Each game has an icon and description
- Hover effects with smooth animations
- Click to select and play
- Back button to return to game list

### 9. **Complete UX Improvements**

- Smooth animations and transitions
- Professional color schemes
- Responsive grid layouts
- Clear visual hierarchy
- Intuitive button interactions
- Loading indicators for AI responses
- Error handling and fallbacks

## 🚀 Getting Started

### Setup

1. Open http://localhost:8000 in your browser
2. Select your current mood using emoji buttons
3. For advanced chatbot: Enter your OpenAI API key

### Using Each Feature

**Chatbot**

- Select mood
- Type message and press Enter or click Send
- AI responds with mood-aware support

**Goals**

- Enter goal text in input field
- Click "Add Goal" or press Enter
- Check box to mark complete
- Click "Delete" to remove

**Tracker**

- View goal completion trends
- See game statistics
- Charts update automatically

**Games**

- Click game card to start
- Select mode (AI or Human if available)
- Follow on-screen instructions
- Results automatically recorded

## 💾 Data Storage

- All data stored in browser's localStorage
- Persists across sessions
- No server required
- Can be cleared in browser settings

## 🔐 Security Notes

- OpenAI API key stored locally only
- Never transmitted to third parties
- Clear before sharing device
- Session-based storage

## 📊 Tracked Statistics

- Daily goal completions
- Game plays by type
- Mood selections (implicit)
- Game performance data

## 🎨 Design Features

- Mood-responsive color gradients
- Smooth transitions (0.3s)
- Responsive breakpoint at 768px
- Professional typography
- Accessible color contrast

## 🔧 Technical Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js
- **API**: OpenAI GPT-4o mini
- **Storage**: LocalStorage
- **No Dependencies**: Pure vanilla JavaScript

## 📱 Responsive Design

- Desktop: 1024px+ (full sidebar)
- Tablet: 768px-1023px (collapsible sidebar)
- Mobile: <768px (slide-in sidebar)

## 🎮 Game AI Features

- Smart Tic Tac Toe AI (center/corner strategy)
- Difficulty: Beginner-friendly
- Human vs AI or Human vs Human modes
- Real-time result display

## 🌟 Future Enhancements

- Sudoku solve feature
- Word search highlighting
- Multiplayer online support
- Voice input for chatbot
- More game varieties
- Backend server integration
- User accounts and cloud sync
