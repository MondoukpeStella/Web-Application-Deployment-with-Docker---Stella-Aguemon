# Dockerize NestJS Project

This projet should help get you started dockeriz your Vue.js app.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Creation

```sh
mkdir projet_name
cd project_name
npm init:
npm install express
```

### Build the Docker image

```sh
docker build -t container_name .
```

### Run our Vue.js app in a Docker container and delete this container

```sh
docker run -it -p 9000:3000 --rm --name image_name container_name
```

### Access our Vue.js app 

Open your browser and go to `http://localhost:9000`
