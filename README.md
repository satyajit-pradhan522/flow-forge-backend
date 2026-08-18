# FlowForge Backend

> Node.js & Express backend for FlowForge — provides REST APIs, authentication, task management, organizations, comments, and MySQL database integration.

## Tech Stack

| Layer          | Technology |
| -------------- | ---------- |
| Runtime        | Node.js    |
| Framework      | Express.js |
| Database       | MySQL      |
| Authentication | JWT        |
| API            | REST       |

## Features

- User authentication
- JWT authorization
- Organization management
- Board & task APIs
- Comments API
- Activity logs
- Role-based permissions
- MySQL database

## Getting Started

### Clone

```bash
git clone https://github.com/satyajit-pradhan522/flow-forge-backend.git
cd flow-forge-backend
```

### Install

```bash
npm install
```

### Environment

Create a `.env` file:

```env
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=flowforge
JWT_SECRET=your_secret_key
```

### Run

```bash
npm run dev
```

## API Base URL

```text
http://localhost:5000/api
```

## Frontend

React frontend repository:

**https://github.com/satyajit-pradhan522/flow-forge-frontend**

## Author

**Satyajit Pradhan**

GitHub: https://github.com/satyajit-pradhan522

## License

This project is for learning and portfolio purposes.
