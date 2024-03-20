Task-1 ToDoList_COD4420

---> CodTech IT Solutions Internship <---

--->
WEB DEVELOPMENT TASK ONE
TO -DO LIST WEB APPLICATION
<---

<---- CODE EXPLAINATION ---->

--->   HTML:
- The HTML file contains the structure of the web page. It has:
  - A `<head>` section containing metadata and references to external CSS and JavaScript files.
  - A `<body>` section where the main content resides.
    - Inside `<body>`, there's a `<section>` with the class `todo`, containing:
      - A `<h2>` heading for the title "To-Do List".
      - An input field for adding new tasks.
      - A button labeled "Add" to add new tasks.
      - An unordered list (`<ul>`) to display the list of tasks.
      - A `<div>` for displaying a counter of total items and a button to delete all tasks.
    - A `<footer>` containing information about the author.

---> CSS:
- The CSS file styles the HTML elements to create a visually appealing layout. Key styles include:
  - Background gradients and colors.
  - Styles for buttons, input fields, and text elements.
  - Layout styles for the To-Do container, list items, and counter.
  - Styling for scrollbars.
  - Styling for the footer.
  - 
---> JavaScript:- The JavaScript file handles the functionality of the To-Do List application. Key functions include:
  - Retrieving tasks from local storage or initializing an empty array if no tasks are stored.
  - Selecting HTML elements needed for interaction.
  - Adding event listeners to buttons and input fields.
  - Functions for adding tasks, displaying tasks, editing tasks, toggling task completion, deleting all tasks, and saving tasks to local storage.
  - These functions manipulate the `todo` array and update the HTML display accordingly.

Overall, the code combines HTML for structure, CSS for styling, and JavaScript for interactivity to create a simple To-Do List web application.
