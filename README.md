- 👋 Hi, I’m @Ashish46357
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Ashish46357/Ashish46357 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
const express = require('express');
const app = express();
const port = 3000; // You can use any port number you prefer

// Define your data as an array of objects
const data = [
  {
    "userId": 10,
    "id": 94,
    "title": "qui qui voluptates illo iste minima",
    "body": "aspernatur expedita soluta quo ab ut similique\nexpedita dolores amet\nsed temporibus distinctio magnam saepe deleniti\nomnis facilis nam ipsum natus sint similique omnis"
  },
  // Add the rest of the objects here
];

// Define the endpoint
app.get('/api/posts', (req, res) => {
  res.json(data);
});

// Start the server
app.listen(port, () => {
  console.log(`Server is running on port ${port}`);
});

