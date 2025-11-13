# Async Code — Advanced Web Dev Project

This project demonstrates **asynchronous JavaScript** operations using `fetch`, modular JS imports, and interaction with REST APIs.  
It allows you to **fetch**, **display**, and **update** user data dynamically without reloading the page.

## Technologies Used
- HTML5
- CSS3 (Bootstrap 5)
- JavaScript (ES6 modules)
- Fetch API (GET and PUT requests)

## Features
- Fetches user data from a local or remote API.
- Displays user cards with avatars, names, and details.
- Allows editing user data inside a Bootstrap modal.
- Updates users asynchronously via PUT requests.

## Files Overview
`index.html`:Main webpage structure using Bootstrap. |
`script.js`:Handles data fetching, DOM updates, and user interactions. |
`fetchData.js`:Utility function to fetch data via GET requests. |
`putData.js`:Utility for PUT requests to update user info. |
`formFactory.js`:Dynamically generates editable user forms. |
`response.json`:(Optional) Mock local data file. |

## How to Run
1. Open `index.html` in your browser.
2. The page will automatically fetch data and display user cards.
3. Click **Edit** on any user to modify their details.

---

### **4. Add your files to Git**
```bash
git add .