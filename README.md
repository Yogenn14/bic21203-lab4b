# BIC21203 Web Development — Lab #4b: Client-Side Scripting (JSON and jQuery)

**Course:** BIC21203 Web Development  
**Academic Session:** 2026/2027  
**Student Name:** Yogenthirran A/L Jagathesan  
**Matric Number:** CI240111  

---

## Project Overview
This repository contains the implementation for Lab #4b covering valid JSON structuring, asynchronous data retrieval via the native JavaScript `fetch()` API, and DOM manipulation/event handling using jQuery 4.0.0.

---

## File Structure
```text
├── books.json        # Question 1: Structured JSON dataset
├── books.html        # Question 2: JSON data retrieval using fetch()
├── jquery-dom.html   # Question 3: jQuery 4.0.0 DOM manipulation & events
├── README.md         # Setup instructions, project overview, and screenshots
└── screenshots/      # Folder containing evidence screenshots
```

---

## Setup & Running Instructions

### Prerequisites
- A modern desktop web browser (e.g., Google Chrome, Microsoft Edge, Mozilla Firefox).
- Visual Studio Code (VS Code).
- **Live Server** extension installed in VS Code.

### How to Run Locally
> **Important:** Do not open `books.html` directly via `file://`. A local HTTP server is required to satisfy browser CORS security policies when fetching local JSON files.

1. Clone or download this repository to your local machine:
   ```bash
   git clone <YOUR_REPOSITORY_URL>
   ```
2. Open the project folder in Visual Studio Code.
3. **Question 1 (`books.json`):** 
   - Open `books.json` to view the data structure or validate via any JSON validator.
4. **Question 2 (`books.html`):**
   - Right-click `books.html` in VS Code and select **Open with Live Server**.
   - The page will open in your browser at `http://127.0.0.1:5500/books.html` and display the parsed book details.
5. **Question 3 (`jquery-dom.html`):**
   - Right-click `jquery-dom.html` and select **Open with Live Server** (or open it directly in your browser).
   - Click the **"Click me"** button to trigger the jQuery alert event.

---

## Screenshots & Evidence

### Question 1: JSON File Structure & Validation
*Screenshot showing `books.json` and successful JSON parsing validation:*  
![Question 1 Code & Validation](screenshots/q1-json-validation.png)

### Question 2: Retrieved JSON Browser Output (Local Server)
*Screenshot of `books.html` displaying the title, author, and grouped genres running on Live Server:*  
![Question 2 Browser Output](screenshots/q2-books-output.png)

*Screenshot of Question 2 user-friendly error handling:*  
![Question 2 Error Handling](screenshots/q2-error-handling.png)

### Question 3: jQuery DOM Updates and Event Handling
*Screenshot of `jquery-dom.html` showing modified text, styled DIV (`.myStyle`), and button click alert:*  
![Question 3 jQuery Output](screenshots/q3-jquery-output.png)