# Docker Template for NodeJS

There is also a postgres database that can be commented out

## Things to know
- Feel free to rename the service and container name for both NodeJS and the Database. If you use this for multiple projects you can run into build issues so renaming will help
- Uncomment env_file in both docker-compose.yml and Dockerfile
- Add `/db` to `.gitignore`

## How to start
```bash
docker compose up
```