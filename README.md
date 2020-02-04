# [Video.js - HTML5 Video Player][vjs]

[![Build Status][travis-icon]][travis-link]
[![Coverage Status][coveralls-icon]][coveralls-link]
[![Greenkeeper badge](https://badges.greenkeeper.io/videojs/video.js.svg)](https://greenkeeper.io/)
[![Slack Status][slack-icon]][slack-link]

[![NPM][npm-icon]][npm-link]

> Video.js is a web video player built from the ground up for an HTML5 world. It supports HTML5 and Flash video, as well as YouTube and Vimeo (through [plugins][plugins]). It supports video playback on desktops and mobile devices. This project was started mid 2010, and the player is now used on over ~~50,000~~ ~~100,000~~ ~~200,000~~ [400,000 websites][builtwith].

## Table of Contents

* [Zero to Hero](#zero-to-hero)
* [Contributing](#contributing)
* [Code of Conduct](#code-of-conduct)
* [License](#license)

## Zero to Hero

In order to make changes to this repository you need to be a member of the Softwire Employees team. Please contact helpdesk to add your account (this can now be done automatically via Bamboo).

After cloning the repository run `npm install` in the project's root directory.
Build the app using `npm run-script build`.

If video.js as a dependancy in one of your projects and you want to make experimental changes to video.js source code you can point your project to your local copy of this repository. Once you have made your changes to video.js/src/ run `npm run-script build`. Navigate to the root directory of the project using video.js as a dependency and run `npm install <path-to-video.js-root-directory>#<branch-name>`.

There can be problems in using your local copy as a dependancy. If you are having trouble you can create a new repo on your personal github account and push your changes there. Make sure to build before you push.

`git remote add upstream <your-git-repo>
git push upstream <branch-name>`

Alternatively you can fork this repo directly. You can then point your project to the new repo using `npm install <your-github-name>/<your-repo-name>#<branch-name>` from the project's root directory.

If you would like to make a pull request to Softwire's video.js repository and you're a member of the Softwire Employee's team: Change the version number of your local copy of video.js in the package.json file. Build, commit the change with a message along the lines of `updated to version-<new-version-number> and built` and then push to your repo. Next create a new branch at Softwire/video.js with name `master-<new-version-number>`. From your own video.js repo create a pull request into the new branch of Softwire/video.js.

## Contributing

Video.js is a free and open source library, and we appreciate any help you're willing to give - whether it's fixing bugs, improving documentation, or suggesting new features. Check out the [contributing guide][contributing] for more!

_Video.js uses [BrowserStack][browserstack] for compatibility testing._

## [Code of Conduct][coc]

Please note that this project is released with a [Contributor Code of Conduct][coc]. By participating in this project you agree to abide by its terms.

## [License][license]

Video.js is [licensed][license] under the Apache License, Version 2.0.

[browserstack]: https://browserstack.com

[builtwith]: https://trends.builtwith.com/media/VideoJS

[contributing]: CONTRIBUTING.md

[coveralls-icon]: https://coveralls.io/repos/github/videojs/video.js/badge.svg?branch=master

[coveralls-link]: https://coveralls.io/github/videojs/video.js?branch=master

[docs]: https://docs.videojs.com

[fastly]: https://www.fastly.com/

[getting-started]: https://videojs.com/getting-started/

[license]: LICENSE

[logo]: https://videojs.com/img/logo.png

[npm-icon]: https://nodei.co/npm/video.js.png?downloads=true&downloadRank=true

[npm-link]: https://nodei.co/npm/video.js/

[options]: docs/guides/options.md

[plugins]: https://videojs.com/plugins/

[slack-icon]: http://slack.videojs.com/badge.svg

[slack-link]: http://slack.videojs.com

[travis-icon]: https://travis-ci.org/videojs/video.js.svg?branch=master

[travis-link]: https://travis-ci.org/videojs/video.js

[vjs]: https://videojs.com

[coc]: CODE_OF_CONDUCT.md
