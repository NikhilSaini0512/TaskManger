# TaskManger
# Task Manager - README
![Task Manager Screenshot]
<img width="1358" alt="Screenshot 2025-04-25 at 7 47 18 PM" src="https://github.com/user-attachments/assets/0997e12d-1476-4f5a-9e2b-2d26d1190001" />

A modern, interactive task management application built with HTML, CSS, and JavaScript that helps users organize, prioritize, and track their tasks efficiently.

## Features

- 📝 **Task Management**
  - Add, edit, and delete tasks
  - Mark tasks as complete
  - Detailed task descriptions
- 🏷️ **Organization**
  - Categorize tasks (Work, Personal, Health, Education)
  - Priority levels (High, Medium, Low)
  - Due dates with reminders
- 🔔 **Smart Reminders**
  - Browser notifications for upcoming tasks
  - Visual alerts for overdue tasks
  - Snooze functionality
- 🎨 **Customizable UI**
  - Light/dark mode toggle
  - Priority-based color coding
  - Responsive design
- 📊 **Productivity Tracking**
  - Completion percentage
  - Task statistics
  - Filtering and sorting options

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Storage**: LocalStorage (No backend required)
- **Icons**: Font Awesome 6
- **Fonts**: Google Fonts (Poppins)

## Usage

1. **Add a Task**
   - Click "Add Task" button
   - Fill in task details (title, description, category, due date, priority)
   - Click "Save Task"

2. **Manage Tasks**
   - ✅ Complete tasks with the check button
   - ✏️ Edit tasks with the edit button
   - 🗑️ Delete tasks with the trash button

3. **Organize**
   - Use the sidebar to filter by category
   - Sort tasks by priority, due date, or creation time
   - Search for specific tasks

4. **Dark Mode**
   - Toggle the moon/sun icon in the top-right corner

## Customization

To customize the app:

1. **Change Categories**
   - Modify the `categoryList` in HTML
   - Update corresponding CSS colors

2. **Adjust Reminder Timing**
   - Edit the `minutesDiff <= 30` value in `checkReminders()` function

3. **Add New Features**
   - Integrate with backend services
   - Add user accounts
   - Implement task sharing

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Edge (latest)
- Safari (latest)

*Note: Notifications require browser permission.*

## License

MIT License

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.


**Enjoy staying productive!** ✨
