
# Dockerized Simple Webpage

## Project Overview
This is a simple webpage running inside Docker using Nginx. 
The page shows "Hello World" and demonstrates how to containerize a basic HTML page with Docker.

## How to Run
1. Build Docker image:
```bash
docker build -t my-webpage .
```

3. Run Docker container:
```bash
docker run -d -p 8080:80 --name webapp my-webpage
```

5. Open in browser:
```bash
http://localhost:8080
```

