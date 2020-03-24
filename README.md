# Ethiopian COVID-19 Emergency Site

A quick way to publish critical information about the Coronavirus / COVID-19 outbreak. Forked from [this repo](https://github.com/maxboeck/emergency-site). Can withstand large amounts of traffic and has off-line support.

## Features

* Static Files generated by [Eleventy](https://11ty.dev)
* Optimized for first Roundtrip (> 14KB)
* Basic Styling for Accessibility
* One Request, Inlined CSS
* [Netlify CMS](https://www.netlifycms.org/) for collaborative Content Editing
* Offline Support with Service Worker

## Getting Started

The easiest way to get started is by forking this repo and deploying it to Netlify. You can do that by clicking this button:  

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/babraham123/emergency-site) 

To customize the site, edit `src/data/meta.json` with your details, and replace the markdown files in `src/posts` with your content.

## Installation

To run this locally, you need to install [Node](https://nodejs.org/en/) first.

**available commands:**

* `npm start`: start development server
* `npm run build`: generate a production build
* `npm run debug`: run eleventy with debug output
