# Nguyen_Linh_HW-3
CSS Cascade, Selection &amp; Pseudo Selectors

# The Ultimate To-Do List

## Description
This is a dynamic and user-friendly To-Do List web application designed to help users organize tasks, track progress, and achieve their goals. The project showcases advanced CSS techniques, including pseudo-selectors (`::after`) and the use of generic selectors to enhance the visual appeal of the application.


## Features
- **Themed Background:** A visually appealing background image relevant to task management.
- **Creative Header:** A header with a meaningful title styled using an `H1` tag and CSS selectors.
- **Dynamic Lists:** Tasks are categorized into "To Do," "In Progress," and "Done."
- **Checkbox Functionality:**
  - Mark tasks as "In Progress" or "Done" using checkboxes.
  - Tasks are styled dynamically when checked.
  - `::after` pseudo-selector is used to add visual feedback for checked items (e.g., ⏰ for "In Progress" and 💯 for "Done").
- **Responsive Design:** The layout adapts to different screen sizes using `flex-wrap`.

## Technologies Used
- **HTML5**: For semantic structure.
- **CSS3**: For advanced styling and dynamic updates.
- **Google Fonts**: Utilized the "Roboto" and "Poppins" font families for a modern look.

## Installation
To get started with this project, follow these steps:

1. Clone the repository to your local machine:
   git clone https://github.com/your-username/end-of-term-todolist.git

2. Navigate to the project directory:
cd end-of-term-todolist

3. Open the index.html file in your browser to see the project in action.

Alternatively, we can run this project on a local server, using tools like Live Server in VS Code or any local server setup.

## Usage
Once the project is running, I will see the following sections:

- To Do: A list of tasks that I need to complete.
- In Progress: A list of tasks I'm currently working on.
- Done: A list of tasks that are completed, with checkboxes to mark the items as done.

## About the Project Components

### HTML
The webpage uses basic HTML elements to build its structure, including:
- `header`: Displays the title and a brief description of the page.
- `main`: Contains three task categories: "To Do", "In Progress", and "Done".
- `article`: Each task list is enclosed in a `article` element for semantic purposes.
- `ul` and `li`: Lists are used to display tasks, with checkboxes to mark tasks as complete.

### CSS
The CSS is used to style the page, enhance layout responsiveness, and add interactive effects. Key features include:
- A background image that creates a thematic look for the page.
- Custom fonts (Roboto and Poppins) to improve text readability and design.
- Responsive layout that adapts to different screen sizes using flexbox.
- Hover effects and color transitions to make the list interactive.
- `::before` and `::after` pseudo-elements to add icons for each list category and provide visual feedback for completed tasks.

### JavaScript
The JavaScript file (optional) can be used to enhance the functionality, such as:
- Saving tasks to LocalStorage to persist user data across page reloads.
- Dynamically adding or removing tasks.
- Implementing additional features like task deadlines or priority levels.

## Contribution Guidelines
1. **Fork the repository**: Create a copy of this repository in your own GitHub account.
2. **Create a feature branch**: Use descriptive names for your branch (e.g., `dev.add-task-storage`).
3. **Commit your changes**: Make sure your commits are clear and well-documented.
4. **Push to the repository**: Push your feature branch to your GitHub repository.
5. **Create a pull request**: Submit a pull request to merge your changes into the main repository.

## History
- **Version 1.0** - Initial release with basic task tracking functionality.
- **Version 1.1** - Added "Observations" section with helpful reminders.
- **Version 1.2** - Improved the layout and styling with CSS.

## Credits
This project was created by Linh Nguyen. The project is built using standard HTML, CSS, and pseudo selectors with custom styles to enhance usability.

## License
This project is licensed under the MIT License - see the LICENSE file for details.