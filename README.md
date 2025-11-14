
# 📝 React Todo App

A beautiful, feature-rich todo application built with React and Vite. Manage your tasks with a modern, intuitive interface featuring a dark theme with cyan accents.

## ✨ Features

- **Add Todos**: Quickly add new tasks with a simple input
- **Mark Complete**: Check off completed tasks
- **Delete Todos**: Remove tasks you no longer need
- **Filter Tasks**: View all, active, or completed todos
- **Persistent Storage**: Todos are saved to localStorage automatically
- **Real-time Stats**: See total, active, and completed task counts
- **Keyboard Support**: Press Enter to add a todo
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Beautiful UI**: Modern dark theme with smooth animations
- **Accessibility**: Full ARIA labels and semantic HTML

## 📦 Tech Stack

- **React 18**: UI library
- **Vite**: Build tool and development server
- **localStorage API**: Data persistence
- **CSS3**: Modern styling with animations

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser and navigate to `http://localhost:5173`

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🎯 How to Use

1. **Add a Todo**: Type in the input field and click "Add" or press Enter
2. **Mark Complete**: Click the checkbox next to a todo to mark it as done
3. **Delete Todo**: Click the "Delete" button to remove a todo
4. **Filter Todos**: Use the filter buttons to view:
   - **All**: Show all todos
   - **Active**: Show only incomplete todos
   - **Completed**: Show only completed todos
5. **View Stats**: Check the bottom stats to see total, active, and completed counts

## 🎨 Design Features

- **Dark Theme**: Modern gradient background
- **Cyan Accents**: Primary accent color with gradients
- **Smooth Animations**: Slide-in effects and transitions
- **Hover Effects**: Interactive feedback on all buttons
- **Responsive Grid**: Adapts to all screen sizes
- **Scrollable List**: Long todo lists scroll smoothly

## 📊 Component Structure

The app is built as a single React component (`App.jsx`) with:
- State management for todos and filters
- localStorage integration for persistence
- Filter logic for different todo views
- Statistics calculation
- Keyboard event handling

## 🔄 Data Structure

Each todo object contains:
```javascript
{
  id: 1234567890,        // Unique identifier (timestamp)
  text: 'Task description', // Todo text
  completed: false       // Completion status
}
```

## 💾 Local Storage

Todos are automatically saved to localStorage under the key `'todos'`. The data persists even after closing and reopening the browser.

### Clear All Data
To clear all todos from browser storage, open DevTools Console and run:
```javascript
localStorage.removeItem('todos');
location.reload();
```

## 🌟 Usage Examples

1. **Add multiple tasks**
2. **Check off tasks as you complete them**
3. **Filter to see only active tasks**
4. **Delete tasks no longer needed**
5. **Track progress with live statistics**

## 🎨 Styling

The todo app features:
- Linear gradients on buttons and background
- Smooth transitions and hover effects
- Active filter button highlighting
- Completed todo styling (strikethrough, reduced opacity)
- Empty state messaging with emoji

## ♿ Accessibility

- ARIA labels on all interactive elements
- Semantic HTML structure
- Keyboard navigation support
- High contrast colors
- Clear visual feedback
- Enter key support for adding todos

## 📱 Responsive Breakpoints

- **Desktop (> 480px)**: Full-size layout with side-by-side buttons
- **Mobile (≤ 480px)**: Stacked layout with single-column input

## 🚀 Performance

- Lightweight: No external UI libraries
- Fast: Instant HMR with Vite
- Efficient: Optimized re-renders with React hooks
- Persistent: localStorage for no API calls

## 🔧 Customization

### Change Theme Colors
Edit colors in `src/index.css`:
- Cyan accent: `#00ffff`
- Dark background: `#1a1a2e`
- Other colors as needed

### Adjust Styling
Modify padding, font-size, and other properties in `src/index.css`

### Change Filter Options
Edit the filter buttons in `src/App.jsx` to customize filter types

## 💡 Future Enhancements

- Edit existing todos
- Due dates and reminders
- Priority levels
- Categories or tags
- Dark/Light theme toggle
- Undo/Redo functionality
- Export todos to CSV
- Recurring todos
- Cloud sync across devices
- Notifications for due tasks

## 📄 License

This project is open source and available for personal and commercial use.

---

Built with ❤️ using React and Vite
