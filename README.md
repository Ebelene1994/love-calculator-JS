❤️ Love Calculator
Objective
The Love Calculator is a fun JavaScript project that estimates the compatibility percentage between two individuals based on their names. The project enhances JavaScript skills, particularly in DOM manipulation, event handling, and basic logic implementation.

Skills Learned
Proficiency in JavaScript fundamentals (functions, event listeners, and DOM interaction).
Understanding of randomization and probability for generating compatibility scores.
Hands-on experience with HTML & CSS for UI/UX improvements.
Implementing input validation and error handling in JavaScript.
Tools Used
JavaScript – Core programming language for logic implementation.
HTML & CSS – To structure and style the user interface.
VS Code / Any Code Editor – For writing and testing the project.
Live Server Extension / Browser – For testing and debugging in real-time.
Steps & Screenshots
📌 Follow these steps to build the Love Calculator:

1. Setting Up the Project
Create an index.html, style.css, and script.js file.
📸 [Insert Screenshot]

2. Designing the UI (HTML & CSS)
Structure the calculator with two input fields and a button.
📸 [Insert Screenshot]

3. Writing JavaScript Logic
Implement a function that calculates a random love percentage.
📸 [Insert Screenshot]

4. Displaying the Result Dynamically
Update the DOM to show results when the button is clicked.
📸 [Insert Screenshot]

💻 Paste Your Code Below
javascript
Copy
Edit
// Love Calculator - JavaScript Code

document.getElementById('calculate').addEventListener('click', function() {
    let name1 = document.getElementById('name1').value.trim();
    let name2 = document.getElementById('name2').value.trim();
    
    if (name1 === "" || name2 === "") {
        alert("Please enter both names!");
        return;
    }

    let loveScore = Math.floor(Math.random() * 100) + 1; // Generate a random score

    document.getElementById('result').innerText = 
        `${name1} ❤️ ${name2} Compatibility: ${loveScore}%`;
});
Demo Preview
🚀 Live Demo: [Your Hosted Link Here]
