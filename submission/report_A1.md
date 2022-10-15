A1.1.

touch Dockerfile to create an empty file called Dockerfile
Fill in the Dockerfile with the necessary instructions
Create a .dockerignore file in the same directory as your Dockerfile
To build the docker image, I ran `docker build . -t florenciamartina/docker-web-app`
Check whether the image is listed by Docker by running `docker images`
Run the image with command `docker run -p 3000:8080 -d florenciamartina/docker-web-app`
Get the container ID with `docker ps` and print the app output with `docker logs <container id>`
Go to [http://localhost:3000](http://localhost:3000)

A1.2.
Create `nginx.conf` and fill with necessary instruction
Fill in the Dockerfile with the necessary instructions
Create a .dockerignore file in the same directory as your Dockerfile
To build the docker image, I ran `docker build . -t florenciamartina/otot_nginx-sample`
Check whether the image is listed by Docker by running `docker images`
Run the image with command `docker run -p 80:80 -d florenciamartina/otot_nginx-sample`
Get the container ID with `docker ps` and print the app output with `docker logs <container id>`
Go to [http://localhost](http://localhost)

A1.3.
Create `default.conf` and fill with necessary instruction
Fill in the Dockerfile with the necessary instructions
Create a `.dockerignore` file in the same directory as your Dockerfile
Run `docker-compose up --build`
Go to [http://localhost](http://localhost)
