# To-Do List App

A simple and elegant task management application built with vanilla HTML, CSS, and JavaScript. Stay organized and track your daily tasks efficiently!

## Features

✨ **Core Features:**
- ✅ Add new tasks with a single click or Enter key
- 📋 View all, active, and completed tasks with filter buttons
- ✔️ Mark tasks as complete/incomplete
- 🗑️ Delete individual tasks
- 🧹 Clear all completed tasks at once
- 📊 View task statistics (total and completed count)
- 💾 Persistent storage using Browser LocalStorage
- 🎨 Beautiful gradient UI with smooth animations
- 📱 Fully responsive design

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients and animations
- **JavaScript (Vanilla)** - No frameworks, pure ES6+
- **LocalStorage API** - For data persistence

## Installation

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server installation required!

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Manohar-NM/To-Do-app-.git
   cd To-Do-app-
   ```

2. **Open the app:**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (if http-server is installed)
     npx http-server
     ```
   - Then navigate to `http://localhost:8000`

## Usage

### Adding Tasks
1. Type your task in the input field
2. Click the **"Add Task"** button or press **Enter**
3. Your task will appear in the list

### Managing Tasks
- **Mark as Complete:** Click the checkbox next to a task
- **Delete Task:** Click the trash icon on any task
- **Filter Tasks:**
  - **All** - View all tasks
  - **Active** - View only incomplete tasks
  - **Completed** - View only completed tasks

### Clearing Completed Tasks
- Click the **"Clear Completed"** button to remove all finished tasks
- Your active tasks will remain

### Statistics
- View the total number of tasks
- See how many tasks are completed

## Project Structure

```
To-Do-app-/
├── index.html      # Main HTML structure
├── styles.css      # All styling and animations
├── script.js       # JavaScript functionality
└── README.md       # Documentation
```

## How It Works

### Data Storage
- All tasks are saved to the browser's LocalStorage
- Data persists even after closing the browser
- Clear browser cache/history to reset tasks

### State Management
- Tasks are stored as an array of objects
- Each task contains: `id`, `text`, and `completed` status
- DOM updates reactively based on filter selection

## Browser Support

- ✅ Chrome/Chromium (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile browsers

## Future Enhancements

- 📅 Due date and priority levels
- 🏷️ Task categories/tags
- 🌙 Dark mode theme
- ⏰ Reminder notifications
- 📤 Export tasks to CSV/JSON
- ☁️ Cloud synchronization
- 🎯 Task repeating/recurring

## License

This project is open source and available under the MIT License.

## Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a new branch
3. Submit a pull request

## Author

**Manohar NM**  
GitHub: [@Manohar-NM](https://github.com/Manohar-NM)

## Support

If you encounter any issues or have suggestions, please open an issue on GitHub.

---

*Built with ❤️ - Happy Task Managing!*
