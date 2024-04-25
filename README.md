
# Docker Challenge

## YUVRAJ SINGH
## 000879357

## CHALLENGE 3

1. Clone the repository

2. Open the folder in VSCode.

3. Copy the files from the challenge3.zip (docker folder) to the cloned repository folder.

4. Add environment variables in the `.env` file.

5. Configure the `docker-compose.yml` file accordingly.

6. Check and update Dockerfiles in the api, db, and nginx folders if necessary.

7. Open the terminal and navigate to the cloned repository folder.

8. Run the following command: "docker-compose up --build"

9. Access the following URLs to test the setup:
 - [http://localhost:8080/api/books]
 - [http://localhost:8080/api/books/1]

10. Confirm that the services are running by running the following command in the terminal:
 ```
 docker-compose ps
 ```

## CHALLENGE 4

1. Copy all the files from the challenge3 folder to the challenge4 folder.

2. Ensure that the Docker containers are running.

3. Make a GET request to [http://localhost:8080/api/stats]to record the initial hostname.

4. Scale up the node-service by running the following command in the terminal:
"docker-compose up --scale node-service=3"

5. Access the URL [http://localhost:8080/api/stats]multiple times and record the hostname each time.

6. To confirm the running services, execute the following command:
"docker-compose ps"


## REFERENCES
1. [Docker Hub](https://hub.docker.com/_/mariadb)
2. [Docker Compose Cheatsheet](https://devhints.io/docker-compose)

