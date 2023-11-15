# FTP-And-SFTP

FTP and SFTP server in docker

## Run

- Create ftp-data and sftp-data directories
- docker compose up -d

### Additional data

- FTP
  - Host: localhost
  - Port: 20
  - User: from .env file (FTP_USER)
  - Password: from .env file (FTP_PASS)

- SFTP
  - Host: localhost
  - Port: 2222
  - User: from .env file (SSH_MASTER_USER)
  - Password: from .env file (SSH_MASTER_PASS)
