# First simple Dockerized - Wadeea

This is a simple Dockerized project using Nginx.

## 🗂️ Files Included

- `Dockerfile`: Builds an Nginx image and copies a custom `index.html` into the container.
- `index.html`: A basic web page to be served by Nginx.

## 🐳 Build Docker Image

```bash
docker build -t wadeea-nginx .

## ▶️ Run the Container

To start the container, run:

```bash
docker run -d -p 80:80 wadeea-nginx


🌐 Access Your Web Page  
After running the container, open your browser and go to:

[http://localhost:80]
📌 Notes
Make sure port 80 is not used by any other application on your system.


