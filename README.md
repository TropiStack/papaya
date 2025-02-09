# Papaya

Papaya is a starter template for building web applications with Nuxt.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/TropiStack/papaya.git
   cd papaya
   ```

2. **Install dependencies:**

   Ensure you have Bun installed, then run:

   ```bash
   bun install
   ```

3. **Build the project:**

   ```bash
   bun run build
   ```

## Usage

### Running Locally

To start the development server locally, run:

```bash
bun dev
```

The server will start on `http://localhost:3000` by default.

### Using Docker

#### Development

To run the server with live reloading using Docker, use the following command:

```bash
docker-compose -p papaya-dev -f docker/docker-compose.yml -f docker/docker-compose.dev.yml up
```

#### Production

To run the server in a production environment, use:

```bash
docker-compose -p papaya-prod -f docker/docker-compose.yml -f docker/docker-compose.prod.yml up
```

## Contributing

Currently, we are not accepting outside contributions. We appreciate your interest and encourage you to check back in the future for any updates regarding contribution opportunities.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
