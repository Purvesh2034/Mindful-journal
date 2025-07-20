# 🌿 Mindful Journal

A beautiful, minimalist journaling app designed to promote mindfulness and emotional awareness. Built with React, TypeScript, and Tailwind CSS.

![Mindful Journal Preview](https://via.placeholder.com/800x400/9CA3AF/FFFFFF?text=Mindful+Journal+Preview)

## ✨ Features

### 📝 **Daily Journaling**
- Clean, distraction-free writing interface
- Custom entry titles and rich text content
- Automatic date tracking and organization
- Edit and update previous entries

### 🎭 **Mood Tracking**
- 5-point emotional scale with visual feedback
- Emoji-based mood selection for intuitive use
- Mood validation before saving entries
- Historical mood pattern analysis

### 💭 **Quote of the Day**
- Rotating inspirational quotes for daily motivation
- Carefully curated collection of mindfulness quotes
- Date-based rotation ensures variety

### 📊 **Insights & Analytics**
- Mood distribution visualization
- Average wellbeing score tracking
- Most common mood identification
- Progress tracking over time

### 💾 **Data Persistence**
- Local storage for privacy and offline access
- No account required - your data stays on your device
- Import/export functionality (coming soon)

## 🚀 Live Demo

Visit the live application: [Mindful Journal](https://lambent-donut-91efc8.netlify.app)

## 🛠️ Tech Stack

- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS with custom sage color palette
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Deployment**: Netlify
- **Storage**: Browser LocalStorage

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mindful-journal.git
   cd mindful-journal
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 🏗️ Build for Production

```bash
# Build the application
npm run build

# Preview the production build
npm run preview
```

## 📁 Project Structure

```
src/
├── components/          # React components
│   ├── EntryList.tsx   # Journal entries list view
│   ├── JournalEntry.tsx # Entry creation/editing
│   ├── MoodTracker.tsx # Mood selection component
│   ├── Navigation.tsx  # App navigation
│   └── QuoteOfTheDay.tsx # Daily quote display
├── types/              # TypeScript type definitions
│   └── index.ts
├── utils/              # Utility functions
│   ├── quotes.ts       # Quote management
│   └── storage.ts      # LocalStorage operations
├── App.tsx             # Main application component
├── main.tsx           # Application entry point
└── index.css          # Global styles
```

## 🎨 Design Philosophy

The app follows a minimalist design approach with:

- **Calming Colors**: Sage green palette promoting tranquility
- **Clean Typography**: Readable fonts with proper hierarchy
- **Subtle Animations**: Smooth transitions and hover effects
- **Responsive Design**: Works seamlessly on all devices
- **Accessibility**: High contrast ratios and keyboard navigation

## 🔧 Configuration

### Tailwind CSS
The app uses a custom color palette defined in `tailwind.config.js`:

```javascript
colors: {
  sage: {
    50: '#f6f7f6',
    // ... full color scale
    900: '#2b332b',
  }
}
```

### Environment Variables
No environment variables required for basic functionality.

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Workflow

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by mindfulness and mental health awareness
- Quotes curated from various wisdom traditions
- Built with modern web technologies for optimal performance

## 📞 Support

If you have any questions or need help, please:

1. Check the [Issues](https://github.com/yourusername/mindful-journal/issues) page
2. Create a new issue if your question isn't answered
3. Follow our [Contributing Guidelines](CONTRIBUTING.md) for bug reports

## 🗺️ Roadmap

- [ ] Data export/import functionality
- [ ] Dark mode support
- [ ] Advanced mood analytics
- [ ] Reminder notifications
- [ ] Cloud sync options
- [ ] Mobile app version

---

**Made with 💚 for mindful reflection and emotional wellbeing**