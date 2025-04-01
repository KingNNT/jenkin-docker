# Jenkins Docker Compose

## How to use ?

1. Clone this repository
2. Run container with command

```
docker compose up -d
```

3. Get initial admin password

```
docker compose exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword
```

4. Active Jenkins

-   Access `http://localhost:6868`
-   Fill above password

5. Install plugins
6. Create first admin user
7. Done
