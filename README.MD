# WordPress Local Development

This project provides a local development environment for WordPress.

## Features

- Easy setup for WordPress development
- Local database and file storage
- Customizable configuration

## Getting Started

1. **Clone the repository:**
  ```bash
  git clone https://github.com/yourusername/wordpress-local.git
  cd wordpress-local
  ```

2. **Install dependencies:**
  - Ensure you have Docker and Docker Compose installed.

3. **Start the environment:**
  ```bash
  docker-compose up -d
  ```

4. **Access WordPress:**
  - Open [http://localhost:8000](http://localhost:8000) in your browser.

## Folder Structure

```
wordpress-local/
├── docker-compose.yml
├── wp-content/
├── README.md
```

## Customization

- Modify `docker-compose.yml` for custom PHP or database versions.
- Place your themes and plugins in `wp-content/`.

## Troubleshooting

- Ensure Docker is running.
- Check port conflicts on `8000`.

## License

MIT License