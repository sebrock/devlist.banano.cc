# BANANO Donation Portal -devlist.banano.cc

## Support Banano developers for building the future of the feeless, instant, rich in potassium cryptocurrency powered by DAG technology disrupting the meme economy that is Banano

[The website](https://devlist.banano.cc/) lists people working on the Banano protocol or related projects.
The goal is to increase the visibility of developers accepting donations.
If you are currently working on Banano related projects, submit a PR to get yourself added!

## Adding yourself to the lists

If you are currently working on Banano related projects or actively contributing to the Banano eco-system, submit a PR with your info [as seen here](https://github.com/joohansson/nanodevlist/edit/master/donatees). Only running a Banano node will not qualify.
Just append your-name.json to the bottom, the list is shuffled on page load.
You can use Markdown in the `description` property.

Name, description and ban_account is mandatory but you can leave any of the other fields blank. The sponsor_link can for example be a link to your Github sponsor page, Patreon or other means of Donation / Sponsorship. An example of such link: [https://github.com/sponsors/luke-jr](https://github.com/sponsors/luke-jr)

Tags are used to filter participants on the site. Please compare with others first, or find inspiration on the [original site](https://bitcoindevlist.com/).

## Local build

[Node.js](https://nodejs.org/en/) is a prerequisite, the dependencies are managed via npm. Linux is recommended but WSL under windows works too.
Once you have cloned this repo, you can setup the packages:

```bash
npm install
```

Create a build and rebuild on file change:

```bash
npm start
```

This will bring up the dev server and pattern library on [localhost:3000](http://localhost:3000). Any changes you make will be updated instantly in the browser.


Special thanks to the original project: https://github.com/dennisreimann/bitcoindevlist.com
