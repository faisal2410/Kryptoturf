<!-- # Example app with [chakra-ui](https://github.com/chakra-ui/chakra-ui)

This example features how to use [chakra-ui](https://github.com/chakra-ui/chakra-ui) as the component library within a Next.js app.

We are connecting the Next.js `_app.js` with `chakra-ui`'s Theme and ColorMode containers so the pages can have app-wide dark/light mode. We are also creating some components which shows the usage of `chakra-ui`'s style props.

## Preview

Preview the example live on [StackBlitz](http://stackblitz.com/):

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/vercel/next.js/tree/canary/examples/with-chakra-ui)

## Deploy your own

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-chakra-ui&project-name=with-chakra-ui&repository-name=with-chakra-ui)

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example with-chakra-ui with-chakra-ui-app
# or
yarn create next-app --example with-chakra-ui with-chakra-ui-app
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).

## Notes

Chakra has supported Gradients and RTL in `v1.1`. To utilize RTL, [add RTL direction and swap](https://chakra-ui.com/docs/features/rtl-support).

If you don't have multi-direction app, you should make `<Html lang="ar" dir="rtl">` inside `_document.js`. -->

<div id="top"></div>
<!--
*** Thanks for checking out the Kryptoturf. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  
  ![The Forum Lab Logo](client/src/images/logo.png "Kryptoturf Logo")

  <h3 align="center">Kryptoturf is a Web 3.0 application that allows users to send transactions through the blockchain.</h3>

  <p align="center">
    <br />
    <a href="https://github.com/ej1seven/Kryptoturf"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://kryptoturf.com/">View Demo</a>
    ·
    <a href="https://github.com/ej1seven/Kryptoturf/issues">Report Bug</a>
    ·
    <a href="https://github.com/ej1seven/Kryptoturf/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

If you follow any of the prominent tech influencers, I'm sure you've come across the word Web 3.0. Web 3.0 is the third generation of the Internet which enables decentralized data interconnection. This new form of Internet enables people to legitimately own their data through transparency. Kryptoturf allows users to connect to their wallet using Metamask, then send ethereum to another account. Kyptoturf shows the last transactions from the related account. Each transaction is associated with a gif that is determined by a keyword supplied by the end user at the time of exchange.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

<!-- - [Next.js](https://nextjs.org/) -->

- [React.js](https://reactjs.org/)
- [Typescript](https://typescriptlang.org/)
- [Solidity](https://docs.soliditylang.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [Vercel](https://vercel.com/)
<!-- - [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Chakra](https://chakra-ui.com/)
- [FontAwesome](https://fontawesome.com/)
- [GraphQl](https:///graphql.org/)
- [ApolloServer](https://www.apollographql.com/)
- [Postgresql](https://postgresql.org/)
- [Redis](https://redis.io/)
- [Nodemailer](https://nodemailer.com/) -->
<!-- - [Docker](https://www.docker.com/)
- [Urql](https://formidable.com/open-source/urql/)
- [MikroOrm](https://mikro-orm.io/)
- [Argon2](https://www.npmjs.com/package/argon2)
- [Dataloader](https://www.npmjs.com/package/dataloader) -->

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple example steps.

### Installation

1. Clone the repo

   ```sh
   git clone https://github.com/Ej1seven/Kryptoturf.git
   ```

2. Install NPM packages
   ```sh
   npm install
   ```
3. Create `.env` file for web

   ```js
   REACT_APP_GIPHY_API = put - your - giphy - api - url;
   ```

<!-- 4. Create `.env` file for server

   ```js
   DATABASE_URL = put - your - postgres - database - url;
   REDIS_URL = put - your - redis - url;
   PORT = put - your - server - port - number;
   SESSION_SECRET = put - your - session - password;
   CORS_ORIGIN = put - your - localhost - url;
   ```

5. Create `.env.production` file for server

   ```js
   SESSION_SECRET = put - your - session - password;
   CORS_ORIGIN = put - your - production - website - url;
   ``` -->

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

### MVP / User Stories

- [x] As a user, I can connect to my wallet using Metamask
- [x] As a user, I can view my transactions
- [x] As a user, send ethereum to another account

See the [open issues](https://github.com/ej1seven/Kryptoturf/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Erik Hunter - <erikhunter@erikhunter.dev>

Project Link: [https://github.com/Ej1seven/Kryptoturf](https://github.com/Ej1seven/Kryptoturf)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/ej1seven/Kryptoturf?style=plastic
[contributors-url]: https://github.com/ej1seven/Kryptoturf/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ej1seven/Kryptoturf.svg?style=plastic
[forks-url]: https://github.com/ej1seven/Kryptoturf/network/members
[stars-shield]: https://img.shields.io/github/stars/ej1seven/Kryptoturf.svg?style=plastic
[stars-url]: https://github.com/ej1seven/Kryptoturf/stargazers
[issues-shield]: https://img.shields.io/github/issues/ej1seven/Kryptoturf.svg?style=plastic
[issues-url]: https://github.com/ej1seven/Kryptoturf/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=plastic&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/erik-hunter/
[product-screenshot]: images/screenshot.png
