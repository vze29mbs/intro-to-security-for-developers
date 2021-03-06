# Intro to Security for Developers

An incomplete introduction to security for developers. Topics include device security, account security, developer tools security, and application security (SSL/TLS, cross-site scripting, authentication systems, information disclosure, and common security headers).

Also check out my [personal security checklist](https://github.com/alulsh/personal-security-checklist) for handy checklist to secure your devices and accounts.

## Presentation

Slides are available on my website at [www.alexandraulsh.com/intro-to-security-for-developers/slides](http://www.alexandraulsh.com/intro-to-security-for-developers/slides/#/). They are hosted on the `gh-pages` branch of this repo.

### View slides locally

If you'd like to view the presentation locally:

```sh
git clone git@github.com:alulsh/intro-to-security-for-developers.git
git checkout gh-pages
cd slides
npm install
npm start
```

Your default web browser should open the slides on `http://localhost:8000/#/` automatically.

### Presentation History

I've given this presentation at the following events. I've tagged each presentation as a release in this repo.

| Event | Date | Release |
|-------|------|---------|
| [Women Who Code DC Tech Talk](https://www.meetup.com/Women-Who-Code-DC/events/235989630/) | Feburary 9th, 2017 | `wwcdc-tech-talk` |
| [Mapbox Miniconf](https://miniconfmapbox.splashthat.com/) | October 8th, 2016 | [`mapbox-miniconf`](https://github.com/alulsh/intro-to-security-for-developers/releases/tag/mapbox-miniconf) |
| [Tech Lady Hackathon #4](http://techladyhackathon.org/) | October 22nd, 2016 | [`techlady-hackathon-2016`](https://github.com/alulsh/intro-to-security-for-developers/releases/tag/techlady-hackathon-2016) |

## Code Samples

This presentation uses code samples written in Node.js to interactively teach security concepts. The code samples are hosted in the default `code-samples` branch.

I do not host these demos on my website since it uses GitHub Pages (can't run a web server) and I don't want live cross-site scripting vulnerabilities on my domain. These demos must be run locally on your machine or on a cloud IDE such as [Cloud9](https://c9.io/).

### Prerequisites

You will need to install [node.js](https://nodejs.org/en/download/) and [npm](https://docs.npmjs.com/getting-started/installing-node) in order to use these code samples. I recommend installing node.js with [nvm](https://github.com/creationix/nvm) (Node Version Manager).

I used node 4.6.0 and npm 2.15.9 to create these code samples, but they may work on earlier or later versions of node/npm. If the samples don't work on your machine, try them with Node 4.6.0 (`nvm install 4.6.0` if you use nvm) and npm 2.15.9 before opening up an issue.

### Installation

To install the code samples:

```sh
git clone git@github.com:alulsh/intro-to-security-for-developers.git
cd <code sample directory>
npm install
npm start
```

For example, to run the cross-site scripting demos:

```sh
git clone git@github.com:alulsh/intro-to-security-for-developers.git
cd xss
npm install
npm start
```

## License

These slides and code samples are open source so I can more easily share them with the world. If you want to re-use them, give me credit or a shout out and let me know! I'd love to hear how you are using them. 

## Questions?

Create a new GitHub issue or Tweet at me - [@AlexUlsh](https://twitter.com/AlexUlsh).