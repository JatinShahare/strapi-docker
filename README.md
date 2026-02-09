I created this project to build and containerize a Strapi v4 application using Docker.

I created a Dockerfile using a Node.js 18 Alpine base image. The Dockerfile installs the required system and Node.js dependencies, copies the application source code, builds the Strapi admin panel, and starts the Strapi server on port 1337.

I configured the application so that environment variables and secrets are not baked into the Docker image. Instead, they are provided at runtime using an external .env file to improve security and portability.

The application can be built and run locally using Docker with port mapping to access the Strapi admin panel.

