
## Public Portfolio Website



data served from `src/profile.js`.

To Update the image go to `src/styles/images.css`  

To change colors, go to `src/styles/style.css`




## Table of Contents
- [Sections](#sections)
- [Getting Started](#getting-started)
- [How to Use](#how-to-use)
- [Change and Customize](#change-and-customize-every-section-according-to-your-need)
- [Deployment](#deployment)

## Sections
✔️ Full screen Intro\
✔️ About Summary\
✔️ Skills\
✔️ Projects\
✔️ Miscellaneous activities\
✔️ Contact Form\
✔️ Social Profile\

To view a live example, **[click here](https://www.dustinpetersen.ca)**.


## Setup

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

You'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer.

```
node@v10.16.0 or higher
npm@6.9.0 or higher
git@2.17.1 or higher
```


## How To Use 

From your command line, clone and run developerFolio:

```bash
# Clone this repository
$ git clone https://github.com/DustinPetersen/portfolio.git

# Go into the repository
$ cd portfolio-template

# Install dependencies
$ npm install

#Start's development server
$ npm start
```

## Change and customize every section according to your need.

#### Personalize page content in `/src/profile.js` & modify it as per your need.

```javascript
/* Change this file to get your Personal Porfolio */


const header = { .... }

const about = { .... }

const skillsBar = { .... }

const projects = { .... }

const miscellaneous = { .... }

const contact = { .... }

const social = { .... }

```


## Deployment
When you are done with the setup, you should host your website online.

We highly recommend to read through the [Deploying on Github Pages](https://create-react-app.dev/docs/deployment/#github-pages) docs for React.


#### Deploying to Netlify

You could also host directly with Netlify by linking your own repository.

[![Deploy To Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/kaustubhai/portfolio-template)

For more information, read [hosting on Netlify](https://create-react-app.dev/docs/deployment/#netlify).


