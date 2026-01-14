# Interactive Flashcard Study App

A powerful, customizable flashcard application with mastery tracking, multiple themes, and seamless card management. Built with vanilla JavaScript, HTML, and CSS - no dependencies required.

## Access
Site is live at https://ian-menachery.github.io/flashcards/

## Features

### 📚 Core Flashcard Functionality
- **Flip cards** to reveal definitions
- **Navigate** between cards with smooth animations
- **Shuffle** cards for randomized study sessions
- **Mastery tracking** - cards disappear after marking "I know this" multiple times
- **Progress statistics** - see how many cards you're learning vs. mastered

### 🎨 Customizable Interface
- **Editable title** - Click the page title to customize it for your study set
- **Colorful Mode** - Toggle vibrant gradient backgrounds with 6 beautiful themes:
  - Purple Dream
  - Ocean Breeze
  - Sunset Glow
  - Fire & Ice
  - Forest Mist
  - Cosmic Fusion
- **Animated gradients** - Smooth, flowing background animations in colorful mode
- **Two aesthetic modes**:
  - Clean, minimal mode with soft greys and elegant typography
  - Vibrant colorful mode with dynamic gradients

### 📝 Card Management
- **Edit Cards** - Access a full list of all cards, edit any card instantly
- **Add New Cards** - Create flashcards on the fly
- **Delete Cards** - Remove cards you no longer need
- **Persistent Storage** - All cards and settings saved to browser localStorage

### ⚙️ Advanced Settings
- **Mastery Threshold** - Set how many times you need to mark "I know this" (1-10)
- **Auto-Advance** - Toggle automatic progression after marking cards
- **Animation Speed** - Choose Fast, Normal, or Slow card transitions
- **Default Study Mode** - Start with all cards or just learning cards
- **Reset Progress** - Clear all mastery progress to start fresh

### ⌨️ Keyboard Shortcuts
- **Space** - Flip current card
- **← →** - Navigate between cards
- **↑** (or K) - Mark "I know this"
- **↓** (or D) - Mark "Don't know"
- **Escape** - Close any open modal
- **Enter** - Save when editing title or cards
- **Ctrl+Enter** - Quick save in card editor

## Getting Started

1. **Open the file** - Simply open the HTML file in any modern web browser
2. **Study existing cards** - 24 FMS Week 2 vocabulary terms are pre-loaded
3. **Customize the title** - Click the title at the top to rename your flashcard set
4. **Edit cards** - Click "Edit Cards" to view, modify, add, or delete flashcards
5. **Adjust settings** - Click the gear icon (⚙️) to customize your study experience

## How to Use

### Studying Cards
1. Read the term on the front of the card
2. Press **Space** or click the card to flip and see the definition
3. Mark **↑ (I Know This)** or **↓ (Don't Know)** based on your knowledge
4. Cards marked as "known" 3 times (by default) will be mastered and hidden
5. Toggle "Show mastered cards" to review them again

### Managing Cards
1. Click **Edit Cards** button
2. Click **+ Add New Card** to create a new flashcard
3. Click on any card content to edit it
4. Click **Delete** button on any card to remove it
5. Changes are saved automatically

### Customizing Appearance
1. Click the **⚙️ Settings** icon
2. Toggle **Colorful Mode** for vibrant backgrounds
3. Select your favorite gradient theme (only visible in colorful mode)
4. Adjust other settings as needed
5. Settings are saved automatically

## Mastery System

The app uses a spaced repetition approach:
- Mark cards you know with **↑** or **K**
- Each card needs to be marked "known" 3 times by default (customizable)
- Mastered cards are hidden to focus on cards you're still learning
- Stats show: Learning vs. Mastered card counts
- Reset all progress anytime in Settings

## Data Persistence

All your data is stored locally in your browser:
- ✅ All flashcards and their content
- ✅ Mastery progress for each card
- ✅ Custom page title
- ✅ All settings and preferences
- ✅ Selected gradient theme

**Note:** Data is browser-specific. Clearing browser data will erase your flashcards and progress.

## Tips for Effective Study

1. **Use the shuffle feature** to avoid memorizing card order
2. **Be honest** with "Know/Don't Know" markings for best results
3. **Adjust mastery threshold** higher for subjects that need more repetition
4. **Take breaks** - the app saves your progress automatically
5. **Review mastered cards** occasionally by toggling "Show mastered cards"
6. **Customize the title** for each subject or chapter you're studying
7. **Disable auto-advance** if you want more time to review each card

## Technical Details

- **File Type:** Single HTML file (self-contained)
- **Dependencies:** None - uses only vanilla JavaScript
- **Storage:** Browser localStorage (persistent)
- **Fonts:** Google Fonts (Inter & Crimson Pro)
- **Compatibility:** Modern browsers (Chrome, Firefox, Safari, Edge)
- **Responsive:** Works on desktop, tablet, and mobile

## Customization

### Adding Your Own Cards
Pre-loaded cards are in the JavaScript section. To start fresh:
1. Click "Edit Cards"
2. Delete existing cards
3. Add your own cards using the "+ Add New Card" button

### Changing Default Settings
Default settings can be modified in the JavaScript `settings` object:
- `masteryThreshold: 3` - Number of correct answers needed
- `colorfulMode: false` - Start with colorful mode on/off
- `autoAdvance: true` - Auto-move to next card
- `animationSpeed: 'normal'` - 'fast', 'normal', or 'slow'
- `gradient: 'purple'` - Default gradient theme

## Keyboard Reference

| Action | Keys |
|--------|------|
| Flip card | Space |
| Next card | → or Right Arrow |
| Previous card | ← or Left Arrow |
| I know this | ↑ or K |
| Don't know | ↓ or D |
| Close modal | Escape |
| Save edit | Enter |
| Quick save | Ctrl+Enter |

## Credits

Built with modern web technologies and thoughtful UX design for optimal studying. Uses Google Fonts (Inter & Crimson Pro) for beautiful typography.

---

**Happy Studying! 📖✨**
