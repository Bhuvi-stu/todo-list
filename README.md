# Todo List

A simple and responsive web app to add, manage, and delete daily tasks with ease.

## Features

Add Tasks – Quickly add new tasks to your to-do list

- Delete Tasks – Remove tasks individually with a single click
- Clear All – (Optional) Add a button to clear the entire list
- Real-Time Updates – Task list updates instantly on interaction
- Responsive Design – Works on both desktop and mobile devices

## How to Use

1.Open the website in your browser (index.html)
2.Type a task in the input box
3.Click the Add button (or press Enter)
4.The task appears in the list below
5.Click the 🗑️ delete icon to remove a task

## How It Works

This webiste:
1.The HTML form collects the user input (task name)
2.JavaScript listens for the "Add" button or Enter key
3.When a task is added:
    -A new list item (<li>) is created and appended to the task list
4.Each task has a delete icon that, when clicked, removes that task
5.Optionally, localStorage can be used to save tasks between sessions

## Limitations

- Tasks are not saved after refreshing the page (unless localStorage is implemented)
- No priority, deadlines, or categorization features
- No edit option for existing tasks
- No drag-and-drop task reordering
- No user login or backend support

## Technologies Used

- HTML5
- CSS3
- JavaScript (Functionality and task logic)

## Future Improvements

- Add localStorage to persist tasks
- Add task completion toggle with checkbox or strikethrough
- Add edit option for existing tasks
- Implement dark mode or theme switching
- Add task categories or tags
- Add drag-and-drop to reorder tasks
- Add search/filter functionality
- Convert into a full-stack version with user accounts and backend database
