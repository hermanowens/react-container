# Retrieve the latest version of Node on Linux Distro from Docker Hub.
FROM node:latest

# Creator/Master behind the madness.
MAINTAINER Herman Owens

# On composition, create a src directory in the root folder of the container.
RUN mkdir /src

# Install node monitoring globally.
RUN npm install nodemon -g

# Set the the src folder as the default directory.
WORKDIR /src

# Add the current local directory to our default directory.
ADD . /src

# Install application dependencies.
RUN npm install

# Allow the container's application to be ran on port 3000
EXPOSE 3000

# Start our application. We're now open for business.
CMD npm start