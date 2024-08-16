# Deployed a two-tier application with AWS and Kubernetes
This is a simple Flask app that interacts with a MySQL database.

# Setup
* Clone the repository
```
git clone https://github.com/your-username/your-repo-name.git
```
* Go to project directory:
```
cd your-repo-name
```
* Create a .env file in the project directory to store your MySQL environment variables:

```
touch .env
```

* Open the .env file and add your MySQL configuration:
```
MYSQL_HOST=mysql
MYSQL_USER=your_username
MYSQL_PASSWORD=your_password
MYSQL_DB=your_database
```
* Start the containers using Docker Compose:
```
docker-compose up --build
```
* Access the Flask app in your web browser:
```
Frontend: http://localhost
Backend: http://localhost:5000
Create the messages table in your MySQL database:
```
* Use a MySQL client or tool (e.g., phpMyAdmin) to execute the following SQL commands:
```
CREATE TABLE messages (
    id INT AUTO_INCREMENT PRIMARY KEY,
    message TEXT
);
```
* To stop and remove the Docker containers, press Ctrl+C in the terminal where the containers are running, or use the following command:
```
docker-compose down
```





































