## 📌 Requirements
- [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/)
- Git

## 🚀 Running the Project

1. **Clone the repository**
   ```sh
   git clone https://github.com/AnastasiaRiabova/goit-pythonweb-hw-02
   cd goit-pythonweb-hw-02
   ```

2. **Start Docker containers**
   ```sh
   docker-compose up --build
   ```

3. **Check application functionality**
   Open in a browser:
   - Main App: [http://localhost:8000/](http://localhost:8000/docs)
   - API documentation: [http://localhost:8000/docs](http://localhost:8000/docs)
   - Health check: [http://localhost:8000/healthchecker](http://localhost:8000/healthchecker)


## 🛠 Commands for Managing Containers

- Stop containers:
  ```sh
  docker-compose down
  ```
- Remove containers and data:
  ```sh
  docker-compose down -v
  ```
- Start in detached mode:
  ```sh
  docker-compose up -d
  ```
- View logs:
  ```sh
  docker-compose logs app
  ```
