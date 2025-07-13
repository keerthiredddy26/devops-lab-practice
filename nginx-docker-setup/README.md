# NGINX Docker Setup

This is a simple Docker project that runs a lightweight NGINX server to serve a custom static HTML page.

## í°³ Built With
- Docker
- NGINX (alpine)

## íº€ How to Run

1. Clone the repo  
```bash
git clone https://github.com/keerthiredddy26/devops-lab-practice.git
cd devops-lab-practice/nginx-docker-setup
```

2. Build the Docker image  
```bash
docker build -t keerthi-nginx-app .
```

3. Run the container  
```bash
docker run -d -p 8080:80 --name keerthi-nginx-container keerthi-nginx-app
```

4. Open your browser and visit:  
```
http://localhost:8080
```

You will see: **Hello from Keerthi's NGINX Docker!**


