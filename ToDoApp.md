
# Project: Build a To-Do List App with HTML, CSS, and JavaScript

In this project, you'll create a simple to-do list app using HTML, CSS, and JavaScript. You’ll practice structuring a web project, working with user input, dynamically updating the DOM, and handling CRUD operations in a web application.

This project is designed to be completed within one day.

For every step:
- Read the brief and acceptance criteria. If unsure, seek help immediately.
- When you’ve fulfilled the acceptance criteria, make a commit and push it to GitHub.
- Move your project card on the associated GitHub project board after completing each step.

---

## Step 1: Fork the Starter Repository

**Brief:**  
Fork the provided GitHub repository to your account to begin the project. Update the `README.md` to include the title of your to-do app.

**Acceptance Criteria:**
- ✅ The repository is forked to your GitHub account.
- ✅ You have cloned the forked repository to your local machine.
- ✅ You have replaced the `README.md` with your own app’s title (e.g., `# My To-Do List App`).

---

## Step 2: Set Up the Project Structure

**Brief:**  
Create the basic file structure for your project.

**Acceptance Criteria:**
- ✅ Your repository contains `index.html`, `style.css`, `script.js` files.
- ✅ All files are correctly linked:
  - `script.js` is linked in `index.html` before the closing `</body>` tag.
  - `style.css` is linked in `index.html` inside the `<head>` tag.

---

## Step 3: Create the Basic HTML Structure

**Brief:**  
Set up the foundational HTML structure for your app.

**Acceptance Criteria:**
- ✅ `index.html` includes a `<h1>` title, an input field for adding tasks, and a button to submit tasks.
- ✅ A `<ul>` or `<div>` container is provided for dynamically displaying tasks.
- ✅ An empty `<p>` or similar element is provided for feedback (e.g., “No tasks to show”).

---

## Step 4: Style the To-Do List

**Brief:**  
Apply some basic CSS styling to your app for a clean layout and better user experience.

We want our app to be styled for a consistent and readable feel.

**Consistency**
- Uniform design elements: The input field, button, and tasks should follow a consistent design pattern (e.g., similar font styles, padding, and colors).
- Spacing and Alignment: The spacing between elements (such as the input field, button, and task list) should be consistent to give the app a structured feel.

**Readability**
- Clear Text Visibility: The font size and color should be easily readable.
- Task List Clarity: The task list should clearly distinguish between completed and incomplete tasks. For example, completed tasks could use a lighter color and a strikethrough effect, while incomplete tasks remain prominent.

**Acceptance Criteria:**
- ✅ The input field and button are styled for consistency and readability.
- ✅ Tasks are displayed as a list with enough space between them.
- ✅ A basic layout is applied (e.g., centering the input field and list).

---

## Step 5: Handle Task Addition

**Brief:**  
Implement the functionality to add tasks to the to-do list.

**Acceptance Criteria:**
- ✅ Users can enter a task in the input field and click the “Add” button to create a new task.
- ✅ The new task is added to the list and displayed on the page.
- ✅ After a task is added, the input field is cleared for a new entry.
- ✅ The app prevents adding empty tasks.

---

## Step 6: Mark Tasks as Completed

**Brief:**  
Allow users to mark tasks as completed.

**Acceptance Criteria:**
- ✅ Each task has a checkbox or a button to mark it as completed.
- ✅ When marked, the task text is styled (e.g., strikethrough or dimmed) to show completion.
- ✅ The completion status is updated in real time.

---

## Step 7: Delete Tasks

**Brief:**  
Allow users to remove tasks from the list.

**Acceptance Criteria:**
- ✅ Each task has a button to delete it.
- ✅ When the delete button is clicked, the task is removed from the list.
- ✅ A confirmation message is shown before the task is deleted (optional).

---

## Step 8: Add Task Persistence with localStorage

**Brief:**  
Store the to-do list tasks in the browser’s `localStorage` so that tasks remain even after the page is refreshed.

**Acceptance Criteria:**
- ✅ Tasks are saved to `localStorage` whenever they are added or removed.
- ✅ Tasks are loaded from `localStorage` when the page is reloaded, showing the same list.
- ✅ The completion status of tasks is also saved and restored.

**Local Storage Examples**

```js
window.localStorage.setItem('username', 'Ben');
```

```js
window.localStorage.setItem('users', JSON.stringify(users));
```

Official Documentation: https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage

---

## Step 9: Implement Task Editing (Optional)

**Brief:**  
Allow users to edit the tasks they have added.

**Acceptance Criteria:**
- ✅ Each task has an option to edit its text.
- ✅ When a task is edited, the updated text is saved and displayed immediately.
- ✅ The edited task is also updated in `localStorage`.

---

## Step 10: Refactor and Comment Your Code

**Brief:**  
Clean up your code for readability and maintainability.

**Acceptance Criteria:**
- ✅ JavaScript functions are properly named and scoped.
- ✅ Comments are added to explain complex code sections.
- ✅ Unused code and console logs are removed.

---

## Step 11: Deploy the App on Netlify

**Brief:**  
Deploy your app to Netlify to make it accessible online.

**Acceptance Criteria:**
- ✅ The app is live and accessible through a URL.
- ✅ A link to your deployed app is included in your `README.md`.
