
# MasDocAI

Aicdex solution attempt

## Project Setup

This project is built using Vite.js for frontend development and Django for the backend.

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v12.0.0 or later)
- npm (v6.0.0 or later) or yarn (v1.22.0 or later)
- Python (v3.8 or later)
- Pipenv


### Installation

1. Clone the repository:

```bash
git clone https://github.com/Shreyas20004/MasDocAI.git
cd MasDocAI
```

2. Install the frontend dependencies:

```bash
npm install
# or
yarn install
```

3. Install the backend dependencies:

```bash
pipenv install
```

### Development

To start the frontend development server, run:

```bash
npm run dev
# or
yarn dev
```

The frontend development server will be running at `http://localhost:3000`.

To start the backend development server, run:

```bash
pipenv run python manage.py runserver
```

The backend development server will be running at `http://localhost:8000`.

### Activate Pipenv Shell

To activate the Pipenv virtual environment shell, run:

```bash
pipenv shell
```

### Building for Production

To build the frontend project for production, run:

```bash
npm run build
# or
yarn build
```

The build artifacts will be stored in the `dist` directory.

### Previewing the Production Build

To locally preview the production build, run:

```bash
npm run serve
# or
yarn serve
```

This will serve the contents of the `dist` folder at `http://localhost:5000`.

### Backend Management

To manage the backend, use Django's management commands. For example, to apply migrations:

```bash
pipenv run python manage.py migrate
```

### Formatting

To format the frontend code, run:

```bash
npm run format
# or
yarn format
```

## Author

[Shreyas20004](https://github.com/Shreyas20004)

