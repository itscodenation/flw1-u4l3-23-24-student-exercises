# Lesson 4.3: APIs and DOM Manipulation

## Objectives
- Review click handlers and DOM manipulation concepts.
- Learn about fetching data from a JSON file and using APIs.
- Apply knowledge to work on projects.

## Key Concepts

### APIs (Application Programming Interfaces)
- **Definition**: A set of protocols and tools for building application software and enabling communication between different software components.
- **Usage**: APIs allow different applications to exchange data and functionalities easily.
- **Examples**: Weather data for weather apps, movie databases for film apps, etc.

### API Syntax in JavaScript
- **Fetching Data**: 
  ```javascript
  fetch(url)
    .then(response => response.json())
    .then(data => {
      console.log(data);
    });
  ```
- **Using Data**: Accessing data from JSON objects, e.g., `data.question` or `data.answers[0].text`.

### DOM Manipulation and Click Handlers
- **Selecting Elements**:
  ```javascript
  let button = document.querySelector("button");
  ```
- **Adding Event Listeners**:
  ```javascript
  button.addEventListener("click", function() {
    console.log("It works!");
  });
  ```

---

Happy Coding! 😊