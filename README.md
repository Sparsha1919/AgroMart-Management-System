# AgroMart

A Node.js backend for **AgroMart**, built with Express and MySQL.

> Replace the short description above with one line about what AgroMart does (for example: "an online marketplace connecting farmers and buyers").

## Tech Stack

- **Runtime:** Node.js
- **Framework:** Express 5
- **Database:** MySQL (via `mysql2`)
- **Other:** `cors` for cross-origin requests, `dotenv` for environment variables

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or newer recommended)
- [MySQL](https://www.mysql.com/) server running locally or remotely

### Installation

```bash
git clone https://github.com/<your-username>/agromart.git
cd agromart
npm install
```

### Environment Variables

Create a `.env` file in the project root (it is already listed in `.gitignore`, so it won't be committed):

```env
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=agromart
```

> Adjust these names to match the variables your code actually reads.

### Database Setup

1. Create the database:
   ```sql
   CREATE DATABASE agromart;
   ```
2. Import the schema (if you have one):
   ```bash
   mysql -u root -p agromart < schema.sql
   ```

### Run the Server

```bash
node index.js
```

The API will be available at `http://localhost:5000` (or whatever `PORT` you set).

## Project Structure

```
agromart/
├── index.js          # Server entry point
├── package.json
├── package-lock.json
├── .env              # Local config (not committed)
└── .gitignore
```

> Update this to match your real folders (routes, controllers, models, etc.).

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET    | `/`      | Example route |

> Fill in your real endpoints here.

## Contributing

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push and open a Pull Request

## License

ISC
