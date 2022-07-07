# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

* Step 1. 
  * **Downlaod and Install Docker** you can download it from [here](https://docs.docker.com/get-docker/)\.

* Step 2.
  * Verify your docker is ready by running the following commands in your
  <br /> <br />
    ```
    docker -v
    ``` 
    and 
    ```
    docker compose -v
    ```

* Step 3.   
  * If above command successfully returns the docker and docker compose version then run using the command
  <br /> <br />
    ```
    docker-compose up
    ``` 
    in the root directory\.
<br /><br /> 
If everything works correctly, the _**backend**_ should be running and be able to connect to your local database\
<br /><br />
You can test this by pointing your browser to [http://localhost:3000/api/ping](http://localhost:3000/api/ping)\
<br /><br />
after backend, check for frontend and backend connection by creating a new user on [http://localhost:3001/register](http://localhost:3001/register)\.
* Step 4.   
  * use this command to run scripts on a running container created in step 3
  <br /> <br />
    ```
    docker exec
    ``` 
