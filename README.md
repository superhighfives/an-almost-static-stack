![An Almost Static Stack](https://i.imgur.com/NStGYap.jpg)

# An almost static stack

An example of using Create React App to bridge the gap between static sites and single page apps. It's the companion to a tutorial of the same name.

Status: archived. Made in 2017, not maintained. Create React App has since been deprecated, so treat this as a snapshot of how I approached the problem at the time. If you're starting something new today, Vite, or a framework that prerenders pages for you like Astro or Next.js, covers the same ground.

Live: https://yadg.surge.sh

Write-up: https://medium.com/superhighfives/an-almost-static-stack-6df0a2791319

## Getting started

```shell
git clone https://github.com/superhighfives/an-almost-static-stack.git
cd an-almost-static-stack
yarn install
yarn start
```

When you're ready to deploy to [Surge](https://surge.sh), run:

```shell
yarn deploy
```

Voila.

If you're not into [Yarn](https://yarnpkg.com/), `npm install`, `npm start`, and `npm run deploy` all work as well. The dependencies are from 2017, so expect to need an older version of Node.

## Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Performance and optimizations

[@stereobooster](https://github.com/stereobooster) put together a great run-through of possible performance optimizations, with links to further reading: https://github.com/stereobooster/react-snap/blob/master/doc/an-almost-static-stack-optimization.md
