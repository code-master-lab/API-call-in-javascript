# 🌐 API Call in JavaScript

This project demonstrates **how to make API calls in JavaScript** using the modern `fetch()` method.  
It is a simple beginner-friendly example that shows how to request data from a public API, read the JSON response, and display it on a webpage.

---

## 🚀 Live Demo  
🔗 https://code-master-lab.github.io/API-call-in-javascript/ 


---

## 📘 What This Project Teaches

- What an API is  
- How JavaScript fetches data from the internet  
- Understanding JSON responses  
- Displaying API data on a webpage  
- Handling errors in API calls  
- Clean and simple front-end JavaScript usage  

---

## 📡 What is an API?

**API (Application Programming Interface)** allows your website/app to communicate with another service.

Example:  
- Weather API → gives weather  
- Movie API → gives movie data  
- User API → gives user details  

JavaScript can call these APIs and show data to the user.

---

## 🧠 How the API Call Works (Simple Example)

```javascript
fetch('https://api.example.com/data')
  .then(response => response.json())
  .then(data => {
    console.log(data); // use the API response here
  })
  .catch(error => {
    console.error("Error:", error);
  });
