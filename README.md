### 📘 `README.md`

```markdown
# 🐳 Flask-Themed-App (Dockerized)

A simple, themed Flask web app running inside a Docker container on **port 8088**, complete with static images and HTML templates.


## 📁 Project Structure
flask-themed-app/
│
├── app.py
├── Dockerfile
├── requirements.txt
│
├── templates/
│   └── index.html
│
└── static/
└── images/
└── sample.jpg

````

---

## 🧑‍💻 Setup & Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/koushikminfy/flask-themed-app.git
cd flask-themed-app
````

### Step 2: Build Docker Image

```bash
docker build -t flask-themed-app .
```

### Step 3: Run the Docker Container on Port 8088

```bash
docker run -p 8088:8088 flask-themed-app
```

### Step 4: View in Browser

Go to: [http://localhost:8088](http://localhost:8088)

---

## 📦 Python Dependencies

Listed in `requirements.txt`:

```
Flask==2.3.2
```

Install locally (if not using Docker):

```bash
pip install -r requirements.txt
```
## 🐙 GitHub Deployment

### Push to GitHub:

```bash
git init
git remote add origin https://github.com/koushikminfy/flask-themed-app.git
git add .
git commit -m "Initial commit - Dockerized Flask app on port 8088"
git branch -M main
git push -u origin main
```

---

## 📸 Screenshot

> ![screenshot](static/images/sample.jpg)

---

## 🧼 Cleanup(if reuired for us s)

To stop and remove the container:

```bash
docker ps
docker stop <container_id>
docker rm <container_id>


---
