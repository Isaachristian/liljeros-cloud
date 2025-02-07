# Liljeros Cloud
Welcome to the liljeros cloud project. This is just a hobby project for running some open source cloud projects such as Seafile and VaultWarden

## Project Structure
Within the project, each individual stack (e.g., Seafile, Vaultwarden, etc.) should have its own directory. The following illustrates this:
```txt
/opt/docker/
│── stack1/
│   ├── docker-compose.yml
│   ├── .env
│   ├── data/ (optional volume storage)
│── stack2/
│   ├── docker-compose.yml
│   ├── .env
```
