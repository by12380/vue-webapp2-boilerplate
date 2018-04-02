# Vue Webapp2 Boilerplate

Vue Webapp2 Boilerplate is a simple application for [Google App Engine](https://appengine.google.com/), using [Vue.js](https://vuejs.org/) on the frontend and [Webapp2](https://webapp2.readthedocs.io/) on the backend. This project can be deployed on Google AppEngine Python Standard Environment.

The frontend was built using the [Vue.js Webpack template](http://vuejs-templates.github.io/webpack/), and uses [vue-router](https://router.vuejs.org/) and [vuex](https://vuex.vuejs.org/); vue-router and vuex store are kept in sync using [vuex-router-sync](https://github.com/vuejs/vuex-router-sync).

It was originally created by [Valmoz](https://github.com/Valmoz), who has an equivalent version using [Vue+Flask](https://github.com/Valmoz/gae-vue-flask-starter), and the original version of this repository [Vue+WebApp2](https://github.com/Valmoz/gae-vue-webapp2-starter).


## Build

``` bash

#clone this repo
git clone https://github.com/chuycepeda/vue-webapp2-boilerplate.git

#go to root
cd vue-webapp2-boilerplate/app

# install dependencies
npm install

# run the frontend at localhost:3000
npm run dev

# run the backend
dev_appserver.py .

# build for production with minification
npm run build

# deploy the application on AppEngine (edit .yaml with your project)
gcloud app deploy app.yaml

```

## License

[MIT](http://opensource.org/licenses/MIT)
