# 🎯 Event Management System (EMS)

Modern, responsive Event Management System for university events with complete CRUD functionality.

## 📁 File Structure

```
event-management-system/
│
├── index.html              # Home page
├── events.html             # All events page
├── create-event.html       # Create new event
├── my-events.html          # User's registered events
├── admin.html              # Admin dashboard
│
├── style.css               # All styling
├── data.js                 # Events database & functions
├── script.js               # Main JavaScript functions
│
└── README.md              # This file
```

## 🚀 Setup Instructions

### Method 1: Simple Setup
1. Create a new folder named `event-management-system`
2. Copy all 8 files into this folder:
   - `index.html`
   - `events.html`
   - `create-event.html`
   - `my-events.html`
   - `admin.html`
   - `style.css`
   - `data.js`
   - `script.js`
3. Open `index.html` in your web browser
4. Done! ✅

### Method 2: Using VS Code
1. Open VS Code
2. Open the project folder
3. Right-click on `index.html`
4. Select "Open with Live Server"

## ✨ Features

### 🏠 Home Page (`index.html`)
- Hero section with call-to-action buttons
- Statistics dashboard (total events, attendees, etc.)
- Featured events showcase
- Quick navigation

### 📅 Events Page (`events.html`)
- Browse all available events
- Filter by category (Technology, Sports, Cultural, etc.)
- Search events by title or description
- Click on any event to view details
- Register for events directly

### ➕ Create Event (`create-event.html`)
- Simple form to create new events
- Required fields validation
- Events submitted for admin approval
- Auto-saves to localStorage

### 👤 My Events (`my-events.html`)
- View all events you've registered for
- Unregister from events
- Empty state with call-to-action
- Quick access to event details

### 🔐 Admin Dashboard (`admin.html`)
- View all events in table format
- Statistics overview
- Approve pending events
- Monitor registrations and capacity
- Event management tools

## 🎨 Design Features

- **Fully Responsive** - Works on mobile, tablet, and desktop
- **Modern UI** - Beautiful gradients and animations
- **Dark Mode Ready** - CSS variables for easy theming
- **Accessibility** - Semantic HTML and proper ARIA labels
- **Fast Loading** - Optimized CSS and JavaScript

## 💾 Data Persistence

- All data stored in browser's localStorage
- Data persists across page refreshes
- No backend required
- Easy to migrate to a real database later

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox & Grid
- **JavaScript (ES6+)** - Vanilla JS, no frameworks
- **localStorage API** - Data persistence

## 📱 Responsive Breakpoints

- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🎯 Key Functions (JavaScript)

### Data Functions (`data.js`)
- `getEvents()` - Get all events
- `saveEvents(events)` - Save events to storage
- `addEvent(event)` - Add new event
- `getEventById(id)` - Get specific event
- `updateEvent(id, updates)` - Update event

### UI Functions (`script.js`)
- `createEventCard(event)` - Generate event card HTML
- `viewEventDetails(id)` - Show event modal
- `registerEvent(id)` - Register for event
- `unregisterEvent(id)` - Unregister from event
- `formatDate(dateString)` - Format dates nicely

## 🎨 Customization

### Change Colors
Edit CSS variables in `style.css`:
```css
:root {
  --primary: #2563eb;        /* Main blue color */
  --primary-dark: #1e40af;   /* Darker blue */
  --secondary: #8b5cf6;      /* Purple accent */
  --success: #10b981;        /* Green for success */
  --danger: #ef4444;         /* Red for errors */
}
```

### Add New Categories
Edit the category options in `create-event.html`:
```html
<option value="YourCategory">Your Category</option>
```

### Modify Event Fields
Edit the event object structure in `data.js`:
```javascript
{
  id: 1,
  title: "Event Title",
  // Add your custom fields here
}
```

## 🔧 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ Internet Explorer (not supported)

## 📝 Future Enhancements

- [ ] Backend integration (Node.js/PHP)
- [ ] User authentication system
- [ ] Email notifications
- [ ] Calendar integration
- [ ] Event reminders
- [ ] Image upload functionality
- [ ] Advanced search filters
- [ ] Export events to PDF
- [ ] Social media sharing

## 🐛 Troubleshooting

### Events not saving?
- Check if localStorage is enabled in your browser
- Clear browser cache and reload

### Styling not loading?
- Make sure `style.css` is in the same folder
- Check browser console for errors

### Images not showing?
- Check internet connection (images load from Unsplash)
- Add fallback images in the code

## 👨‍💻 Development

### Testing Locally
1. Make changes to files
2. Save
3. Refresh browser (Ctrl + R / Cmd + R)

### Debugging
- Open Browser DevTools (F12)
- Check Console tab for JavaScript errors
- Check Network tab for loading issues

## 📄 License

Free to use for educational and personal projects.

## 🤝 Contributing

Feel free to fork and improve! Suggestions welcome.

## 📞 Support

For issues or questions, check the code comments or reach out!

---

**Made with ❤️ for university event management**

Happy Event Managing! 🎉
