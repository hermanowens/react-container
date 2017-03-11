#React Starter Pack within Docker Container

Deployment-ready docker container with a React environment setup.

Technologies used:
- Docker
    - Web Container
        - App:
            - Express
            - NodeJS
            - React
            - Webpack
    - Redis Container

Follow the "Local Setup" section in the  "Node with Docker: Continuous Integration" tutorial, link provided in resources below. Then, use the commands below to start the docker container and run the application.

***Note: Depending on the name you used to create your docker-machine, you may have a different name than dev.***

```console
eval "$(docker-machine env dev)"
docker-compose up
```

Resources:
- [Node with Docker: Continuous Integration](http://mherman.org/blog/2015/03/06/node-with-docker-continuous-integration-and-delivery/#.WLj59hIrLGK)
- [React on the Server: Build a Universal App](https://scotch.io/tutorials/react-on-the-server-for-beginners-build-a-universal-react-and-node-app)

Future Updates:
- Include [MERN](http://mern.io/) as the universal application library for the starter pack.
- Include [MobX](https://mobx.js.org/) as the state manager library for the starter pack.
- Better Documentation later, I promise.
