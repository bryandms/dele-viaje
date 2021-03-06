<h4 align="center">
  <img src="logo-en.png" alt="Dele Viaje Logo" />
</h4>

<div align="center">

[Why with Graphql?](#why-with-graphql) | [Installation](#installation) | [Contribute](#contribute) | [License](#license)

[:es:](README-ES.md) | [:us:](README.md)

[![Build Status][img-travis-ci]][travis-ci] [![license][img-license-badge]][MIT]

</div>

Dele Viaje is a Graphql API to recommend tourist sites based on user search criteria using the Euclidean distance algorithm.

### Why with Graphql?
Dele Viaje was created to help anyone find tourist sites, for this reason, anyone could use the API to create new applications, but maybe not all people want to consult all the available information about a tourist site, maybe they just want know the name, location and hours of operation, or maybe the name and services, it is at this point where Graphql comes to help us, because thanks to Graphql we can define the data we want to know about the tourist sites.

Graphql allows to have a single endpoint where the information of the multiple resources and fields is requested, only indicating what they need. No more overfetching and underfetching.

### Installation
Step 1: Clone or download the repo.

Step 2: Switch to your repository's directory.
```
cd /path/to/your/repo
```

Step 3: Install dependencies.
```
npm install
```

Step 4:  Duplicate the .env-example file and rename it to .env and change the environment variables.
```
cp .env-example .env
```

Step 5: Run the server.
```
npm start
```

Step 6: Run the tests.
```
npm test
```

### Contribute
If you find a bug, something to improve, you want to add a new functionality please create the issue on GitHub or if you want to create a PR, create it. In this way we help other people who use Dele Viaje.

### License
See [license](LICENSE)

[img-license-badge]:https://img.shields.io/github/license/bryandms/dele-viaje-graphql.svg?label=LICENSE&style=for-the-badge
[img-travis-ci]:https://img.shields.io/travis/com/bryandms/dele-viaje-graphql.svg?style=for-the-badge

[MIT]:https://opensource.org/licenses/MIT
[travis-ci]:https://travis-ci.org/bryandms/dele-viaje-graphql
