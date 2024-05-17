ARG NODE_VERSION=19.8.1

FROM node:${NODE_VERSION}-alpine

WORKDIR /application

COPY . .

# Expose the port that the application listens on.
EXPOSE 8000

# Run the application.
CMD ["node" , "src/server.js"]
