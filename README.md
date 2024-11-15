**<ins>Name</ins>:-** TIRUMALA RATNAKAR

**<ins>COMPANY</ins>:-** CODTECH IT SOLUTION

**<ins>ID</ins>:-** CT12DS2478

**<ins>DOMAIN</ins>:-** FRONTEND

**<ins>DURATION</ins>:-** SEPTEMBER 20th,2024 to NOVEMBER 20th,2024

**<ins>Mentor</ins>:-** Neel Santhosh Kumar

# <ins>Project Name</ins> :- Interactive Quiz Application

### Overview of the Code

The given code represents the structure and basic functionality for a **To-Do List** web application. Here's a detailed breakdown:

---

#### **HTML Structure**
1. **Document Metadata**:
   - Specifies the document type (`<!DOCTYPE html>`).
   - Sets the language attribute (`lang="en"`) to English.
   - Defines character encoding as UTF-8 and ensures responsiveness with the `viewport` meta tag.
   - Contains a `<title>` element within a `<marquee>` tag, which is not a standard or recommended practice.

2. **External Resources**:
   - Links an external CSS file (`style.css`) to style the application.
   - Loads an external JavaScript file (`script.js`) to handle the application's behavior.

3. **Body Content**:
   - A **container div** encloses the main content of the To-Do List application.
   - **To-Do List Application**:
     - Includes a **title section**:
       - Displays a heading (`<h1>`) with "To-Do List".
       - Shows a logo (`<img>` tag) sourced from the `images/Logo.jpeg` file.
     - A **row for input**:
       - A text input box (`<input type="text">`) where users can type their tasks.
       - A date input box (`<input type="date">`) to select task deadlines.
       - Two buttons (`<button>`) to add tasks to the list, each linked to the same `addTask()` function.
     - A **task list container**:
       - Uses an unordered list (`<ul>`) with the ID `list-container` and a class `scroll` to display tasks dynamically.
   - The **JavaScript functionality** is loaded via `script.js`.

---

#### **Key Features and Observations**
1. **Dynamic Functionality**:
   - The `addTask()` function (expected to be defined in `script.js`) is intended to add tasks to the list dynamically.
   
2. **Date Input**:
   - Includes a date picker to associate deadlines with tasks.
   - The `min` attribute for the date input is set but not given a specific value, likely requiring JavaScript logic to dynamically assign today's date.

3. **Visual and Accessibility Elements**:
   - A scrollable task list area (`class="scroll"`) ensures smooth task management for larger lists.
   - The UI design incorporates a title, logo, and input elements for user interaction.

4. **Redundancies**:
   - Two buttons (`btn1` and `btn2`) appear to serve the same purpose (`onclick="addTask()"`), which could be streamlined.

5. **Outdated Practices**:
   - The `<marquee>` tag is deprecated and should not be used in modern web development.

## <ins>OUTPUT</ins>:

![Screenshot 2024-11-15 121055](https://github.com/user-attachments/assets/0f6beb75-8d75-41f6-9fa4-92e6b7fe8202)

![Screenshot 2024-11-15 121125](https://github.com/user-attachments/assets/818aad5f-6238-494b-a000-d31a33e9fee5)

![Screenshot 2024-11-15 121213](https://github.com/user-attachments/assets/4a69d727-4311-425c-bcc3-d39b368884ed)
