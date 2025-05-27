# Hassena's Learning Hub

A beginner-friendly Node.js and Express project.

## How to Run

1. Run `npm install` to install dependencies.
2. Start the server using `npm start`.
3. Visit `http://localhost:3000` to see the result.

## Files

### server.js
```js
const express = require('express');
const app = express();
const port = 3000;

app.get('/', (req, res) => {
  res.send('<h1>Welcome to Hassena\'s Learning Hub</h1><p>Learning to code starts here.</p>');
});

app.listen(port, () => {
  console.log(`Server is running at http://localhost:${port}`);
});
