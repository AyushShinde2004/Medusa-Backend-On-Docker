# 🐍 Medusa Backend on Docker

A Dockerized setup for the Medusa backend, enabling rapid development and deployment of headless e-commerce solutions.

---

## 🚀 Features

- 🐳 Docker-based deployment for streamlined setup
- ⚙️ Configurable environment via `.env` file
- 🧪 Integration testing with Jest
- 📦 Dependency management with Yarn
- 🛠️ TypeScript support for robust development

---

## 📁 Project Structure

```
├── .medusa/             # Medusa-specific configurations
├── .vscode/             # VSCode editor settings
├── integration-tests/   # Integration test suites
├── src/                 # Source code for the Medusa backend
├── .dockerignore        # Files and directories to ignore in Docker builds
├── .env                 # Environment variable definitions
├── .gitignore           # Git ignore rules
├── .yarnrc.yml          # Yarn configuration
├── Dockerfile           # Docker build instructions
├── docker-compose.yml   # Docker Compose configuration
├── instrumentation.ts   # Instrumentation setup
├── jest.config.js       # Jest testing configuration
├── medusa-config.ts     # Medusa configuration
├── package.json         # Project metadata and dependencies
├── package-lock.json    # NPM lockfile
├── tsconfig.json        # TypeScript compiler options
├── yarn.lock            # Yarn lockfile
```

---

## 🛠️ Prerequisites

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Node.js](https://nodejs.org/) (v16 or higher)
- [Yarn](https://classic.yarnpkg.com/en/docs/install/)

---

## ⚙️ Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/AyushShinde2004/Medusa-Backend-On-Docker.git
   cd Medusa-Backend-On-Docker
   ```

2. **Configure Environment Variables**

   Create a `.env` file in the root directory and define the necessary environment variables. Refer to the `.env.example` file for guidance.

3. **Build and Start the Containers**

   ```bash
   docker-compose up --build
   ```

   This command builds the Docker images and starts the containers.

4. **Access the Medusa Backend**

   Once the containers are running, the Medusa backend should be accessible at:

   ```
   http://localhost:9000
   ```

---

## 🧪 Running Tests

To execute the integration tests:

```bash
yarn test
```

This command runs the test suites defined in the `integration-tests/` directory using Jest.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Credits

Developed by [Ayush Shinde](https://github.com/AyushShinde2004)

---
