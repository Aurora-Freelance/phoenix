# Phoenix

![License](https://img.shields.io/badge/license-MIT-blue.svg)

**Phoenix** is a crypto and stock trading insights platform designed to **aggressively rebuild a small portfolio from ashes**.

## Features

- **Real-Time Data:** Access up-to-date information on cryptocurrencies and stocks.
- **Trading Insights:** Receive actionable recommendations to optimize your investments.
- **Portfolio Management:** Track and manage your portfolio performance efficiently.
- **Concurrent Development:** Seamlessly run both client and server environments.

## Project Structure

```
/project-root
├── /client
│   ├── /public
│   ├── /src
│   ├── package.json
│   └── README.md
├── /server
│   ├── /controllers
│   ├── /middleware
│   ├── /models
│   ├── /routes
│   ├── package.json
│   └── README.md
├── docker-compose.yml
├── README.md
└── .gitignore
```

## Getting Started

### Prerequisites

- **Node.js** (v14+)
- **npm** (v6+)
- **Docker** (optional for containerization)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Aurora-Frelance/phoenix.git
   cd phoenix
   ```

2. **Install Dependencies**
   ```bash
   npm run install-all
   ```

### Running the Application

- **Start Client and Server Concurrently**
  ```bash
  npm start
  ```
  - **Client:** [http://localhost:3000](http://localhost:3000)
  - **Server:** [http://localhost:8000](http://localhost:8000)

- **Using Docker**
  ```bash
  docker-compose up --build
  ```
  - **Client:** [http://localhost:3000](http://localhost:3000)
  - **Server:** [http://localhost:8000](http://localhost:8000)

## Scripts

- **Start Application:**
  Runs both client and server.
  ```bash
  npm start
  ```

- **Install All Dependencies:**
  Installs for both client and server.
  ```bash
  npm run install-all
  ```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

**Aurora Bailey**

- [GitHub](https://github.com/Aurora-Frelance)
```i
