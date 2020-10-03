## Prerequisites

- [Node](https://nodejs.org/en/)
- [npm](https://nodejs.org/en/) / [yarn](https://yarnpkg.com/)
- [docker](https://www.docker.com/)


## Usage

To start the project, first clone the project and start with the following command

```jsx
git clone https://github.com/rennerwins/thaitrade-press-release.git

yarn start
#or
npm run start
```

This will spin up Docker container with default port `2368` (port can be change in `docker-compose.yml` file).

Once Docker container is ready, open up you browser and go to [http://localhost:2368](http://localhost:2368) and you'll see the landing page of the site.


## Commands

`yarn start` - Start up Docker container

`yarn restart` - Restart Docker container

`yarn stop` - Stop Docker container

### Notes
To get a better understanding of how to customize Ghost CMS please read the [document](https://ghost.org/docs/api/v3/handlebars-themes/).

You might also need some basic knowledge of [handlebars](https://handlebarsjs.com/guide/expressions.html) template engine.
