# Manga Reader

A clone manga reader app made with Vue, Nuxt, GraphQL, Apollo, Bulma


* [Nuxt](https://nuxtjs.org/?ref=tipe) and [Vue](https://vuejs.org/?ref=tipe)
* [GraphQL](http://graphql.org/?ref=tipe) and [Apollo](https://www.apollographql.com/client?ref=tipe)
* [Bulma](https://bulma.io/?ref=tipe)


## Getting started
* Clone this repo
* Install dependences
	* `yarn` or `npm install`
* Run `yarn dev` or `npm run dev`'
	* this will start Nuxt dev Universal mode

## Things to notice
Apollo will fetch the content from your `tutorial` folder on your Tipe account. Becuase Nuxt is running in Universal mode, the content is rendered with the App and then cached and transferred to the client side.

Most of the content you see on the app is from Tipe. Take a look at the `/apollo/query/` folder. Notice the queries and how they relate to your content on the Tipe dashboard in the `tutorial` folder. There's no reason why all the content on this starter app couldn't be stored in Tipe. It's non-user generated, and as a developer, you should never hard code content.

## License
MIT
