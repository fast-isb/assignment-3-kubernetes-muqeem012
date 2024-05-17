ARG NODE_VERSION=14

FROM node:${NODE_VERSION}-alpine

WORKDIR /application

# Copy the rest of the source files into the image.
COPY . .

RUN npm install

# Expose the port that the application listens on.
EXPOSE 3000

# Run the application.
CMD ["npm", "start"]
