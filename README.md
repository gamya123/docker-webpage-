cat > README.md <<EOL
# Dockerized Simple Webpage

## Project Overview
This is a simple webpage running inside Docker using Nginx. 
The page shows "Hello World" and demonstrates how to containerize a basic HTML page with Docker.

## Screenshot
![Webpage Screenshot](screenshot.png)

## How to Run
1. Build Docker image:
\`\`\`
docker build -t my-webpage .
\`\`\`

2. Run Docker container:
\`\`\`
docker run -d -p 8080:80 --name webapp my-webpage
\`\`\`

3. Open in browser:
http://localhost:8080
EOL
