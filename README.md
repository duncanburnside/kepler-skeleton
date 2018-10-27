# KeplerJs Skeleton Project

This repo gives you all you need to quickly create your working project based on KeplerJs


## Deploy a new instance on Heroku
Host your own KeplerJs instance for **FREE** with [One-Click Deploy](https://heroku.com/deploy).

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/Keplerjs/kepler-skeleton/tree/master)


### Clone this repository

```
git clone git@github.com:Keplerjs/kepler-skeleton.git
cd kepler-skeleton
```
or in https:
```
git clone https://github.com/Keplerjs/kepler-skeleton.git
```

### Install dependencies and Run

```
npm install
npm start
```

### Customization

The best way to add, extend or modify features in KeplerJs is to create a [Kepler plugin](http://docs.keplerjs.io/plugin-js.html).
You can find in the documentation the guidelines for doing this.
Here there is also a skeleton of Kepler plugin inside the *packages* directory, it can be enabled or disabled through the standard Meteor commands *meteor add* or *meteor remove*:

```
meteor add keplerjs:plugin-skeleton
```

Default **.meteor/packages** content, uncomment for enable more plugins
```
keplerjs:base
keplerjs:theme
keplerjs:plugin-skeleton
#keplerjs:api
#keplerjs:edit
#keplerjs:admin
#keplerjs:stats
#keplerjs:upload
#keplerjs:share
#keplerjs:geoinfo
#keplerjs:osm
#keplerjs:favorites
#keplerjs:convers
#keplerjs:notifs
#keplerjs:pois
#keplerjs:tracks
#keplerjs:categories
```
