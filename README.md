# Interwiki

This is the Interwiki module made by the [SCP Wiki](https://scpwiki.com),
the English-speaking branch of SCP, for all branches of the [international
SCP](http://scp-int.wikidot.com/) and [Wanderers'
Library](http://wanderers-library.wikidot.com/) communities.

This Interwiki module is [forked](https://github.com/SCP-CN-Tech/Interwiki)
from [SCP 基金会](http://scp-wiki-cn.wikidot.com/), the Chinese branch of
SCP, and was originally made by **[@7happy7](https://github.com/7happy7)**
and **[@Sekai-s](https://github.com/Sekai-s)**.

The Interwiki is for cross-linking translations of articles between
international branches. Placed on any page in the SCP or WL community, the
Interwiki will list pages with a matching 'fullname' / 'UNIX name' / URL
from other branches of that community.

The Interwiki can be styled with CSS and has no limit on the number of
styles that can be applied to it.

# Development

Install locally with [NPM](https://www.npmjs.com/): `npm install`

We use [Prettier](https://prettier.io/) for formatting: `npm run format`

To test locally, run `npm run serve`, note the local IP for the server, and
follow the usual setup instructions using it as the hosted location. On
page refresh the iframe will be reloaded with any new changes without
needing to be recompiled.

To build, run `npm run build`. Output can be found in the `dist/` directly,
and all files present should be hosted for usage.

All JavaScript should be written in ES5.

