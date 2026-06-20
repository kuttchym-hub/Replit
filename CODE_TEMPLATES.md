# 💻 CODE TEMPLATES - Ready to Use
## Copy & Paste Templates for Your Projects

---

## 📝 TABLE OF CONTENTS
1. [HTML Templates](#html-templates)
2. [CSS Templates](#css-templates)
3. [JavaScript Templates](#javascript-templates)
4. [Node.js Templates](#nodejs-templates)
5. [Python Templates](#python-templates)
6. [Configuration Templates](#configuration-templates)

---

## 🌐 HTML TEMPLATES

### Template 1: Responsive Landing Page

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="My awesome landing page">
    <meta name="keywords" content="landing, page, responsive">
    <title>Welcome</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav class="navbar">
            <div class="logo">MyLogo</div>
            <menu class="nav-menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </menu>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>Welcome to My Site</h1>
            <p>This is a responsive landing page</p>
            <button class="cta-btn">Get Started</button>
        </section>

        <section id="about" class="about">
            <h2>About Me</h2>
            <p>Learn more about what I do...</p>
        </section>

        <section id="contact" class="contact">
            <h2>Contact</h2>
            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 My Website. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
```

### Template 2: Blog Post Layout

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Post Title</title>
    <link rel="stylesheet" href="blog.css">
</head>
<body>
    <article class="blog-post">
        <header class="post-header">
            <h1>Amazing Blog Post Title</h1>
            <div class="meta">
                <span class="author">By Your Name</span>
                <span class="date">June 20, 2026</span>
                <span class="reading-time">5 min read</span>
            </div>
        </header>

        <img src="featured-image.jpg" alt="Post thumbnail" class="featured-image">

        <div class="post-content">
            <h2>Section 1</h2>
            <p>Your content here...</p>

            <h2>Section 2</h2>
            <p>More content here...</p>

            <h3>Subsection</h3>
            <ul>
                <li>Point 1</li>
                <li>Point 2</li>
                <li>Point 3</li>
            </ul>
        </div>

        <div class="post-footer">
            <div class="tags">
                <span class="tag">android</span>
                <span class="tag">development</span>
                <span class="tag">tutorial</span>
            </div>
        </div>
    </article>

    <aside class="sidebar">
        <h3>Related Posts</h3>
        <ul class="related-posts">
            <li><a href="#">Post 1</a></li>
            <li><a href="#">Post 2</a></li>
        </ul>
    </aside>
</body>
</html>
```

### Template 3: Portfolio Page

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <p>Android Developer | Web Developer</p>
    </header>

    <main>
        <section class="projects">
            <h2>My Projects</h2>
            <div class="project-grid">
                <div class="project-card">
                    <img src="project1.jpg" alt="Project 1">
                    <h3>Project One</h3>
                    <p>Description of project one</p>
                    <div class="tags">
                        <span>React</span>
                        <span>CSS</span>
                    </div>
                    <a href="#" class="btn">View</a>
                </div>

                <div class="project-card">
                    <img src="project2.jpg" alt="Project 2">
                    <h3>Project Two</h3>
                    <p>Description of project two</p>
                    <div class="tags">
                        <span>Node.js</span>
                        <span>MongoDB</span>
                    </div>
                    <a href="#" class="btn">View</a>
                </div>
            </div>
        </section>

        <section class="skills">
            <h2>Skills</h2>
            <div class="skill-list">
                <div class="skill-item">
                    <span>JavaScript</span>
                    <div class="progress-bar">
                        <div class="progress" style="width: 90%"></div>
                    </div>
                </div>
                <div class="skill-item">
                    <span>Python</span>
                    <div class="progress-bar">
                        <div class="progress" style="width: 85%"></div>
                    </div>
                </div>
            </div>
        </section>
    </main>
</body>
</html>
```

---

## 🎨 CSS TEMPLATES

### Template 1: Modern Clean CSS

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --text-color: #333;
    --light-bg: #f4f4f4;
    --white: #ffffff;
    --border-radius: 8px;
    --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: var(--text-color);
    background-color: var(--light-bg);
}

header {
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    color: var(--white);
    padding: 2rem 0;
    box-shadow: var(--shadow);
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1rem;
}

.nav-menu {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-menu a {
    color: var(--white);
    text-decoration: none;
    transition: opacity 0.3s ease;
}

.nav-menu a:hover {
    opacity: 0.8;
}

main {
    max-width: 1200px;
    margin: 2rem auto;
    padding: 0 1rem;
}

section {
    background: var(--white);
    padding: 2rem;
    margin-bottom: 2rem;
    border-radius: var(--border-radius);
    box-shadow: var(--shadow);
}

h1, h2, h3 {
    color: var(--primary-color);
    margin-bottom: 1rem;
}

button, .btn {
    background: var(--primary-color);
    color: var(--white);
    border: none;
    padding: 0.8rem 1.5rem;
    border-radius: var(--border-radius);
    cursor: pointer;
    transition: all 0.3s ease;
}

button:hover, .btn:hover {
    background: var(--secondary-color);
    transform: translateY(-2px);
    box-shadow: 0 6px 12px rgba(102, 126, 234, 0.4);
}

/* Responsive */
@media (max-width: 768px) {
    .nav-menu {
        flex-direction: column;
        gap: 1rem;
    }

    section {
        padding: 1rem;
    }

    h1 {
        font-size: 1.5rem;
    }
}
```

### Template 2: Dark Mode CSS

```css
:root {
    --bg-dark: #1a1a1a;
    --bg-darker: #0f0f0f;
    --text-light: #e0e0e0;
    --text-lighter: #ffffff;
    --accent: #667eea;
    --accent-hover: #764ba2;
}

body {
    background-color: var(--bg-dark);
    color: var(--text-light);
    font-family: 'Segoe UI', sans-serif;
}

.card {
    background-color: var(--bg-darker);
    border: 1px solid rgba(255, 255, 255, 0.1);
    border-radius: 8px;
    padding: 1.5rem;
    transition: all 0.3s ease;
}

.card:hover {
    border-color: var(--accent);
    box-shadow: 0 0 20px rgba(102, 126, 234, 0.2);
}

/* Dark mode button */
.dark-mode-toggle {
    position: fixed;
    top: 1rem;
    right: 1rem;
    background: var(--accent);
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    border-radius: 50px;
    cursor: pointer;
}
```

### Template 3: Grid Layout CSS

```css
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin: 2rem 0;
}

.grid-item {
    background: white;
    padding: 1.5rem;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.grid-item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 4px;
    margin-bottom: 1rem;
}

@media (max-width: 768px) {
    .grid {
        grid-template-columns: 1fr;
    }
}
```

---

## 📜 JAVASCRIPT TEMPLATES

### Template 1: Fetch API Data

```javascript
// Fetch data from API
async function fetchData(url) {
    try {
        const response = await fetch(url);
        
        if (!response.ok) {
            throw new Error(`HTTP error! status: ${response.status}`);
        }
        
        const data = await response.json();
        console.log('Data fetched:', data);
        return data;
    } catch (error) {
        console.error('Fetch error:', error);
    }
}

// Usage
fetchData('http://localhost:3000/api/data');

// POST request
async function postData(url, data) {
    try {
        const response = await fetch(url, {
            method: 'POST',
            headers: {
                'Content-Type': 'application/json',
            },
            body: JSON.stringify(data)
        });
        
        const result = await response.json();
        console.log('Success:', result);
        return result;
    } catch (error) {
        console.error('Error:', error);
    }
}

// Usage
postData('http://localhost:3000/api/add', { name: 'John' });
```

### Template 2: DOM Manipulation

```javascript
// Select elements
const button = document.getElementById('myBtn');
const elements = document.querySelectorAll('.item');
const first = document.querySelector('.container');

// Add event listener
button.addEventListener('click', function() {
    console.log('Button clicked!');
});

// Add class
button.classList.add('active');

// Remove class
button.classList.remove('inactive');

// Toggle class
button.classList.toggle('visible');

// Change text
button.textContent = 'Click me!';

// Change HTML
button.innerHTML = '<span>Click</span>';

// Create element
const newDiv = document.createElement('div');
newDiv.textContent = 'New element';
document.body.appendChild(newDiv);

// Remove element
newDiv.remove();

// Get attribute
const href = button.getAttribute('href');

// Set attribute
button.setAttribute('data-id', '123');
```

### Template 3: Local Storage

```javascript
// Save to local storage
localStorage.setItem('username', 'John');

// Get from local storage
const username = localStorage.getItem('username');

// Remove from local storage
localStorage.removeItem('username');

// Clear all
localStorage.clear();

// Check if exists
if (localStorage.getItem('username')) {
    console.log('User exists');
}

// Save object
const user = { name: 'John', age: 25 };
localStorage.setItem('user', JSON.stringify(user));

// Get object
const savedUser = JSON.parse(localStorage.getItem('user'));
```

---

## 🚀 NODE.JS TEMPLATES

### Template 1: Basic Express Server

```javascript
const express = require('express');
const cors = require('cors');
const app = express();
const PORT = 3000;

// Middleware
app.use(cors());
app.use(express.json());

// Routes
app.get('/', (req, res) => {
    res.json({ message: 'Welcome!' });
});

app.get('/api/hello', (req, res) => {
    res.json({ greeting: 'Hello, World!' });
});

app.post('/api/data', (req, res) => {
    const { name } = req.body;
    res.json({ message: `Hello, ${name}!` });
});

app.get('/api/users/:id', (req, res) => {
    const { id } = req.params;
    res.json({ user_id: id });
});

// Error handling
app.use((err, req, res, next) => {
    console.error(err);
    res.status(500).json({ error: 'Server error' });
});

// Start server
app.listen(PORT, () => {
    console.log(`Server running on http://localhost:${PORT}`);
});
```

### Template 2: Database with Express

```javascript
const express = require('express');
const app = express();

app.use(express.json());

// Simple in-memory database
let items = [
    { id: 1, name: 'Item 1' },
    { id: 2, name: 'Item 2' }
];

// Get all items
app.get('/api/items', (req, res) => {
    res.json(items);
});

// Get single item
app.get('/api/items/:id', (req, res) => {
    const item = items.find(i => i.id === parseInt(req.params.id));
    if (!item) return res.status(404).json({ error: 'Not found' });
    res.json(item);
});

// Add item
app.post('/api/items', (req, res) => {
    const newItem = {
        id: items.length > 0 ? Math.max(...items.map(i => i.id)) + 1 : 1,
        name: req.body.name
    };
    items.push(newItem);
    res.status(201).json(newItem);
});

// Update item
app.put('/api/items/:id', (req, res) => {
    const item = items.find(i => i.id === parseInt(req.params.id));
    if (!item) return res.status(404).json({ error: 'Not found' });
    
    item.name = req.body.name || item.name;
    res.json(item);
});

// Delete item
app.delete('/api/items/:id', (req, res) => {
    items = items.filter(i => i.id !== parseInt(req.params.id));
    res.json({ message: 'Deleted' });
});

app.listen(3000, () => console.log('Server running...'));
```

### Template 3: package.json

```json
{
  "name": "my-api",
  "version": "1.0.0",
  "description": "My first API",
  "main": "server.js",
  "scripts": {
    "start": "node server.js",
    "dev": "node server.js",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": ["api", "node", "express"],
  "author": "Your Name",
  "license": "MIT",
  "dependencies": {
    "express": "^4.18.2",
    "cors": "^2.8.5",
    "dotenv": "^16.0.3"
  }
}
```

---

## 🐍 PYTHON TEMPLATES

### Template 1: Basic Flask App

```python
from flask import Flask, jsonify, request
from datetime import datetime

app = Flask(__name__)

@app.route('/', methods=['GET'])
def home():
    return jsonify({
        'message': 'Welcome to Flask!',
        'timestamp': datetime.now().isoformat()
    })

@app.route('/api/hello', methods=['GET'])
def hello():
    return jsonify({'greeting': 'Hello, World!'})

@app.route('/api/data', methods=['POST'])
def process_data():
    data = request.json
    name = data.get('name', 'Guest')
    return jsonify({'message': f'Hello, {name}!'})

@app.route('/api/users/<int:user_id>', methods=['GET'])
def get_user(user_id):
    return jsonify({'user_id': user_id, 'name': 'John Doe'})

@app.errorhandler(404)
def not_found(error):
    return jsonify({'error': 'Not found'}), 404

if __name__ == '__main__':
    app.run(host='0.0.0.0', port=5000, debug=True)
```

### Template 2: Flask with Database

```python
from flask import Flask, jsonify, request

app = Flask(__name__)

# Simple in-memory database
items = [
    {'id': 1, 'name': 'Item 1'},
    {'id': 2, 'name': 'Item 2'}
]

@app.route('/api/items', methods=['GET'])
def get_items():
    return jsonify(items)

@app.route('/api/items/<int:item_id>', methods=['GET'])
def get_item(item_id):
    item = next((i for i in items if i['id'] == item_id), None)
    if not item:
        return jsonify({'error': 'Not found'}), 404
    return jsonify(item)

@app.route('/api/items', methods=['POST'])
def add_item():
    new_item = {
        'id': max([i['id'] for i in items]) + 1 if items else 1,
        'name': request.json.get('name')
    }
    items.append(new_item)
    return jsonify(new_item), 201

@app.route('/api/items/<int:item_id>', methods=['PUT'])
def update_item(item_id):
    item = next((i for i in items if i['id'] == item_id), None)
    if not item:
        return jsonify({'error': 'Not found'}), 404
    
    item['name'] = request.json.get('name', item['name'])
    return jsonify(item)

@app.route('/api/items/<int:item_id>', methods=['DELETE'])
def delete_item(item_id):
    global items
    items = [i for i in items if i['id'] != item_id]
    return jsonify({'message': 'Deleted'})

if __name__ == '__main__':
    app.run(debug=True)
```

---

## ⚙️ CONFIGURATION TEMPLATES

### Template 1: .gitignore

```
# Node
node_modules/
npm-debug.log
package-lock.json

# Python
__pycache__/
*.py[cod]
*.egg-info/
dist/
build/
.Python

# Environment
.env
.env.local
.vscode/
.idea/

# OS
.DS_Store
Thumbs.db

# Logs
logs/
*.log

# Temporary
tmp/
temp/
*.tmp
```

### Template 2: .env Template

```
# Server
PORT=3000
NODE_ENV=development

# Database
DB_HOST=localhost
DB_PORT=27017
DB_NAME=mydb
DB_USER=admin
DB_PASSWORD=secret

# API Keys
API_KEY=your_api_key
SECRET_KEY=your_secret

# URLs
API_URL=http://localhost:3000
FRONTEND_URL=http://localhost:3000
```

### Template 3: package.json (Advanced)

```json
{
  "name": "full-stack-app",
  "version": "1.0.0",
  "description": "Full-stack application",
  "main": "server.js",
  "scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js",
    "test": "jest",
    "lint": "eslint ."
  },
  "keywords": [],
  "author": "",
  "license": "MIT",
  "dependencies": {
    "express": "^4.18.2",
    "cors": "^2.8.5",
    "dotenv": "^16.0.3",
    "mongoose": "^7.0.0",
    "bcryptjs": "^2.4.3",
    "jsonwebtoken": "^9.0.0"
  },
  "devDependencies": {
    "nodemon": "^2.0.20",
    "jest": "^29.5.0"
  }
}
```

---

## 🎯 HOW TO USE THESE TEMPLATES

1. **Copy the template** you want
2. **Create a new file** in Acode
3. **Paste the code**
4. **Modify for your needs**
5. **Save and test**
6. **Push to GitHub**

---

## ✅ TEMPLATE CHECKLIST

Before using any template:
- [ ] Copy entire code
- [ ] Save with correct filename
- [ ] Install required dependencies
- [ ] Replace placeholder text
- [ ] Test locally
- [ ] Check for errors
- [ ] Push to GitHub

---

**Happy coding! Use these templates to speed up development! 🚀**

Last Updated: June 2026
