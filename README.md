
**ThoughtStream™** - Transform your thoughts into organized, visual streams of productivity.

Designed with low-code simplicity and high-performance functionality, ThoughtStream is a unique tool for streamlining your thoughts to avoid mental clutter and achieve your goals. It uses formatting and style adjustments to communicate your thoughts in a visually appealing and organized manner, and is fairly customizable.

 Built with Firebase and vanilla JavaScript, this web application is designed to create a visual and persistent canvas where tasks can remain persistent without being intrusive.
# ThoughtStream

A visual task management and productivity application that organizes your thoughts into streams and displays tasks as floating, priority-based elements on a dynamic canvas.

## ✨ Features

### 🎯 Visual Task Management
- **Priority-based visual representation**: Tasks appear as floating elements with different sizes, colors, and styles based on priority levels
- **Dynamic positioning**: Tasks are positioned across the screen based on urgency and importance
- **Interactive hover effects**: Tasks scale and highlight when hovered over

### 📊 Priority System
- **lowLeisure**: Small, subtle tasks for leisure activities
- **low**: Basic priority tasks with minimal styling
- **lightMedium**: Medium-low priority with moderate emphasis
- **medium**: Standard priority tasks
- **normalHigh**: High priority with increased visibility
- **urgentHigh**: Urgent tasks with strong visual emphasis
- **overdue**: Maximum priority with bold, attention-grabbing styling

### 🌊 Stream Organization
- **Multiple streams**: Organize tasks into different life areas (All, School, Home, Health, Brock, Composing, Coding)
- **Tab-based navigation**: Switch between different thought streams easily
- **Stream-specific task filtering**: View tasks relevant to specific contexts

### ⏰ Time Management
- **Built-in timer**: Pomodoro-style timer for focused work sessions
- **Due date tracking**: Automatic priority adjustment based on due dates
- **Time estimation**: Add time estimates to tasks

### 🎨 Customizable Themes
- **Multiple visual themes**: Switch between different color schemes and styles
- **Dynamic backgrounds**: Animated gradient backgrounds
- **Theme persistence**: Your theme preference is saved

### 💾 Data Persistence
- **Local storage**: Tasks and settings saved locally
- **Firebase integration**: Cloud backup and sync capabilities
- **Import/Export**: Backup and restore your task data

### 📱 Modern Interface
- **Responsive design**: Works on desktop and mobile devices
- **Modal-based editing**: Clean, focused editing experience
- **Keyboard shortcuts**: Quick task creation and navigation

## 🚀 Getting Started

### Prerequisites
- Modern web browser with JavaScript enabled
- Node.js (for local development server)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd ThoughtStream
   ```

2. **Serve the application**
   
   Using the included Node.js server:
   ```bash
   node public/server.js
   ```
   
   Or using Firebase hosting:
   ```bash
   firebase serve
   ```

3. **Open in browser**
   Navigate to `http://localhost:3000`

## 🎮 How to Use

### Creating Tasks
1. Click anywhere on the main area to create a new task
2. Set the task title, priority, and optional due date
3. Tasks automatically position themselves based on priority

### Managing Streams
1. Use the tab system at the top to switch between different streams
2. Create new streams by clicking the "+" button
3. Assign tasks to specific streams during creation

### Timer Usage
1. Click on any task to open its detail modal
2. Set a timer duration and click start
3. Use the pause/resume controls as needed

### Theme Customization
1. Click the settings icon to open theme options
2. Choose from available themes
3. Your selection is automatically saved

## 🏗️ Architecture

### Frontend
- **Vanilla JavaScript**: No framework dependencies for maximum performance
- **CSS3**: Advanced animations and responsive design
- **HTML5**: Semantic markup and modern web standards

### Backend Services
- **Firebase Realtime Database**: Cloud data storage
- **Firebase Hosting**: Static site hosting
- **Local storage**: Offline-first data persistence

### Key Components
- **Task Engine**: Handles task creation, positioning, and priority management
- **Stream Manager**: Organizes tasks into different contexts
- **Timer System**: Pomodoro-style focus timer
- **Theme System**: Dynamic styling and visual customization

## 📁 Project Structure

```
ThoughtStream/
├── public/
│   ├── index.html          # Main application
│   ├── server.js           # Local development server
│   └── assets/
│       ├── fonts/          # Custom fonts
│       └── styles/         # Theme stylesheets
├── firebase.json           # Firebase configuration
├── firestore.rules         # Database security rules
└── README.md              # This file
```

## 🛠️ Development

### Local Development
```bash
# Start the local server
node public/server.js

# Or use Firebase CLI
firebase serve
```

### Firebase Deployment
```bash
# Deploy to Firebase Hosting
firebase deploy
```

## 🎯 Use Cases

- **Academic Planning**: Organize assignments, projects, and study sessions
- **Personal Productivity**: Manage daily tasks, habits, and goals
- **Creative Projects**: Track composition, coding, and artistic endeavors
- **Health & Wellness**: Monitor fitness goals and health tasks
- **Professional Work**: Organize work tasks and deadlines

## 🤝 Contributing
Not actively seeking contribution, but feel free to fork for private use and improve as you like. If you want to incorporate ThoguhtStream into your own projects, feel free to contact me for guidance

## 📄 License

All rights reserved. This code may not be used, copied, modified, or distributed without explicit permission from the author.

# thoughtstream
# thoughtstream
