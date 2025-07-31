# minio-server
A secure minio server for publicly serving the local storage data.

## Setup Instructions
- Clone the repository.

- Replace values in .env with your configuration.

- Make sure DNS points to your server IP (both A and/or AAAA records).

- Run Certbot once to get the initial certificate:
```bash
docker compose run certbot
```
- Start the full stack
```bash
docker compose up -d
```
