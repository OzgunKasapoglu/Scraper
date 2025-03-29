# Web Scraping Bot: Quotes to Database

## 📖 Project Description
A Node.js bot that scrapes quotes, authors, and tags, processes the data, and stores it in a structured MySQL database. Designed as a learning project for web scraping, database integration, and Docker containerization. Includes a **1-command setup** for seamless local development.

---

## 🛠 Technologies & Libraries
| Technology          | Purpose                                                                 |
|---------------------|-------------------------------------------------------------------------|
| **Node.js**         | Runtime environment for executing JavaScript                           |
| **Puppeteer**       | Headless browser automation to scrape dynamic web content              |
| **MySQL2**          | MySQL client for Node.js to interact with the database                  |
| **Dotenv**          | Securely loads database credentials from environment variables         |
| **Docker**          | Containerization to isolate dependencies (Node.js, Chrome, MySQL)      |
| **Docker Compose**  | Orchestrates multi-container setup with networking and volume management |

---

## 🐳 Docker Setup
### **Prerequisites**
1. Install Docker Desktop (https://www.docker.com/products/docker-desktop/).

### **Run the Project**
```bash
# Clone the repository
git clone https://github.com/OzgunKasapoglu/scraper.git
cd web-scraping-quotes-bot

# Start the containers (Node.js app + MySQL)
docker-compose up
```
