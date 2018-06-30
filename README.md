<h1 align="center">
  <br>
  <a href="https://tipe.io?ref=github-starter"><img src="https://cdn.tipe.io/tipe/tgn.png?dpr=2&w=800&auto=compress" alt="Tipe + GraphQL + Vue" width="800"></a>
  <br>
  Tipe + GraphQL + Vue
  <br>
</h1>


> :tada: Starter repo for [Vue](https://vuejs.org/?ref=tipe) and [Nuxt](https://nuxtjs.org/?ref=tipe), together with [GraphQL](http://graphql.org/?ref=tipe) and [Tipe](https://tipe.io/?ref=github-starter) :100:

## What is Tipe
[Tipe](https://tipe.io?ref=github-starter), pronounced *type*, is a content backend for all your apps. If you have any non-user generated content in your apps, you should use Tipe to manage it. You and content creators can use our web app to create and publish content, then consume that same content with our **REST** and **GraphQL** API's. 

## What is this repo
This repo is a solid starting point for anyone looking to build a Universal, SPA, or Static site with Vue and Tipe. The repo consists of a simple blog application that consumes content from Tipe via GraphQL.

## Tech in this repo
* [Nuxt](https://nuxtjs.org/?ref=tipe) and [Vue](https://vuejs.org/?ref=tipe)
* [GraphQL](http://graphql.org/?ref=tipe) and [Apollo](https://www.apollographql.com/client?ref=tipe)
* [Bulma](https://bulma.io/?ref=tipe)


## Things you'll need
* Node *(version is whatever Nuxt needs)*
* An account on [Tipe](https://tipe.io?ref=github-starter)
	* **Tipe is free right now!**

## Getting started
* Clone this repo
* Install dependences
	* `yarn` or `npm install`
* Create a `.env` file on the **root** of this repo. Copy over the contents from `.sample.env`.
* Replace the env values with your API Key and Org ID from the Tipe dashboard.
* Run `yarn dev` or `npm dev`'
	* this will start Nuxt dev Universal mode

## Things to notice
Apollo will fetch the content from your `tutorial` folder on your Tipe account. Becuase Nuxt is running in Universal mode, the content is rendered with the App and then cached and transferred to the client side.

Most of the content you see on the app is from Tipe. Take a look at the `/apollo/query/` folder. Notice the queries and how they relate to your content on the Tipe dashboard in the `tutorial` folder. There's no reason why all the content on this starter app couldn't be stored in Tipe. It's non-user generated, and as a developer, you should never hard code content.

## Contributing
* Fork and cut a PR, we'll check it out :sunglasses:

## Related
* [Tipe + GraphQL + Vue starter](https://github.com/tipeio/tipe-vue-starter)
* [Tipe + GraphQL + React starter](https://github.com/tipeio/tipe-react-starter)

## Tipe Community
* [Twitter @TipeIO](https://twitter.com/tipeio)
* [Facebook](https://facebook.com/TipeCMS)
* [Slack](https://chat.tipe.io/)
* [Github](https://github.com/tipeio)
* [Linkedin](https://www.linkedin.com/company/tipeio/)
* [awesome-tipe](https://github.com/tipeio/awesome-tipe)

## License
MIT
