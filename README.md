Project Video Link:  https://drive.google.com/file/d/1hQUtXx4hUUciWmD-uE2rk_jrkKyT58-c/view?usp=sharing

==================== Project Description ====================

![Screenshot 2024-05-31 160821](https://github.com/jay-228/React-commit-rw/assets/122542095/ded5d7ee-4efa-4cb5-bf6e-5750a714fca1)

**Objective:**
The objective of this assignment is to practice creating and managing form inputs in a React application. You will use various input types and state management techniques to collect and log student information.

**Task:**
Create a form with multiple input types such as text, email, password, select, and radio buttons. The form should be designed to collect various pieces of information from students. Once the user fills out the form, the values should be collected and logged to the console in the form of an object.

**Instructions:**

1. **Form Component:**
    - Create a new file named `StudentForm.js`.
    - Define a functional component named `StudentForm`.
    - Use multiple input types: text, email, password, select, and radio buttons.
    - Use **`useState`** for managing the state of individual form inputs.
    - Use a single **`useState`** hook to manage multiple states within the form.
    - Add a submit button to the form that, when clicked, logs the collected values to the console in the form of an object.
    - Ensure the form is user-friendly and efficiently collects the necessary data.
    - Export the `StudentForm` component using **`export default StudentForm`**.
    
    Example structure (without actual code):
    
    - **Text Input:** Collect the student's full name.
    - **Email Input:** Collect the student's email address.
    - **Password Input:** Collect a password for the student's account.
    - **Select Input:** Allow the student to select their grade (e.g., Freshman, Sophomore, Junior, Senior).
    - **Radio Buttons:** Collect the student's gender (e.g., Male, Female, Other).
2. **App Component:**
    - Create a new file named `App.js`.
    - Import the `StudentForm` component at the top of the file.
    - Use the `StudentForm` component within the **`App`** component's render method.
    - Export the `App` component using **`export default App`**.
3. **Final Steps:**
    - Ensure all form inputs are correctly managed using `useState`.
    - Log the form values as an object to the console upon form submission.
