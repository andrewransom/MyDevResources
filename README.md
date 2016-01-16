# Intro - Andrew's Dev Resources

This is really just a dump of useful tidibts and libraries I've come across as I learn.

---

# Javascript

## General


---
## React
* Nick Raienko's [Awesome React List](https://github.com/enaqx/awesome-react)

### Tools & UI Components

* [React Dock](https://github.com/alexkuz/react-dock)
* [React Hot Loader](https://github.com/gaearon/react-hot-loader)
  * uses a proxy that creates proxies for your methods. Saving a file replaces the stored methods
  * Leverage's webpack feature called hot-mode replacement
* [React Drag and Drop - React DnD](http://gaearon.github.io/react-dnd/)
* [React Motion](https://github.com/chenglou/react-motion)
 * A good [tutorial](https://medium.com/@nashvail/a-gentle-introduction-to-react-motion-dc50dd9f2459#.26qz2jrdh) on a UI action button


---
## Redux
* Dan Abramov's [Tutorial Videos](https://egghead.io/series/getting-started-with-redux)
 * And the community notes

### Useful Blog Posts
* J Longster's [The Seasonal Blog Redux](http://jlongster.com/The-Seasonal-Blog-Redux)
 * other good links at the end of this article
* J Longster's [Simple Routing with Redux](http://jlongster.com/A-Simple-Way-to-Route-with-Redux)
 * Use [react-router](https://github.com/rackt/react-router) and just keep the URL as state in Redux store

### Starter Kits
* [React-Redux Univseral Hot Example](https://github.com/erikras/react-redux-universal-hot-example)
 * Quite comprehensive. Good scalable structure.
* [Universal Redux](https://github.com/bdefore/universal-redux)
  * Simpler, has a JWT example

### Tools

* [redux-devtools](https://github.com/gaearon/redux-devtools)
 * based on react-dock, dock-monitor, and log-monitor
* [redux-form](http://erikras.github.io/redux-form)
 * a slick way to get forms going - not sure if it's good for more than the basics yet


---
## Immutable
* Redux requires that the store be immutable
* Use the Immutable Library ( https://facebook.github.io/immutable-js/ )
* A good video on the benefits immutablilty : [Immutability, Interactivity & Javascript](https://www.youtube.com/watch?v=mS264h8KGwk)
 * by David Nolen (Cognitect) Interesting [Datomic](http://cognitect.com/datomic) time data engine
 * https://github.com/glenjamin/transit-immutable-js
 * J Longster's [Immutable Libraries](https://gist.github.com/jlongster/bce43d9be633da55053f)

### Tutorials
* Youtube Video: [Immutable Javascript: You can't change this](https://www.youtube.com/watch?v=wA98Coal4jk)
* Lee Byron's [Using Immutable.js with React](https://www.youtube.com/watch?v=YFP8lbdZ0cs)
* James Longster's [Using Immutable Data Structures in Javascript](http://jlongster.com/Using-Immutable-Data-Structures-in-JavaScript)
---
## WebPack

## Tutorials
* Pete Hunt's [Webpack How To](https://github.com/petehunt/webpack-howto)

---
## Getting Started with with React and Redux

In a console window

```
mkdir project-name
cd project-name
npm init -y
```

Then start getting the dev-support libraries going:

```
npm install --save-dev babel-cli babel-preset-es2015
npm install --save-dev mocha chai
```


Add the following line to your .babelrc file:
```
{
  "presets": ["es2015"]
}
```
