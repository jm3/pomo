# Pomo - a better tomato timer

[![Greenkeeper badge](https://badges.greenkeeper.io/jm3/pomo.svg)](https://greenkeeper.io/)

## “Because productive doesn’t have to mean ugly”

[This project][url] is a CSS Grid experiment doing double duty as a
productivity timer.

![screenshot][screenshot]

## SETUP

    yarn # or alternately: npm install
    npm start

## WARN

- scss parsing triggered by the include in index.js - including in HTML not necessary / doesn't run scss

## TECH

Uses:

- [Parcel][parcel] for asset bundling, live-reload, and minification
- [Pug][pug] for templating
- Stylelint for style pruning
- SCSS for now... (but maybe soon PostCSS?)

## HUMANS.TXT

- Podcasts: YKS, RTP, RSP

[url]: https://pomo.jm3.net/
[parcel]: https://parceljs.org/
[pug]: https://parceljs.org/pug.html
[screenshot]: https://raw.githubusercontent.com/jm3/pomo/master/docs/pomo-mobile+web@0.5x.png
