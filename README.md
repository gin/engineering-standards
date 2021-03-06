# Clearmatics Engineering Standards

## Git 

* Follow these [seven rules][1] for writing a commit message
* Use [signed commits][2]
* Use the [git flow][3] branching strategy
* Master branches are protected 
* 1 review is required before merging 
* Delete branch after accepting merge request

## Go

* [`go fmt` your code][4]
* Use [`dep`][5] for dependency management

## Python
* Use [Pylint][pylint] on your code
* Follow the [PEP 8][PEP8] guide

## Node.js

* Use ES6 features (ES6 is the same as ECMAScript 2015, and ECMAScript 6) as described in [MDN web docs][mozilla_es6], or better in the [official ECMA][official_es6]
* Use a [eslint][eslint] with the [AirBnB][eslint_airbnb] style
* Add NPM scripts (for everything that it is needed and possible)
* Install packages locally (avoid using global packages)

## Frontend

* Use [webcomponents][mozilla_webcomponents] when possible ([React](https://reactjs.org/), [Vue](https://vuejs.org/) and similar are acceptable and more widely supported)
* More simple components is better than large complex components (each component should do one thing only)
* Manage the state of the webapp separately from the UI (and document it in the code)
* Use JS bundlers (like [webpack](https://webpack.js.org/))
* Create clear README on how to build and deploy the frontend

## Solidity

* Use a [common language][sm_desc] when talking about smart contracts
* Follow the Solidity [coding style][15]
* Follow smart contract [best practices][16], tools, engineering convention and other
* Use [Solhint][solhint] to lint your contracts


## Testing

* Aim for 70% plus test coverage levels
* Integration tests are more valuable than unit tests
* Integrate tests with CI and run on each commit

## Continuous Integration

* [Use Travis CI][6]

## Packaging

* Use [Docker][7] for packaging and push public images to [Docker Hub][8]

## Open Source Repositories

* [Add a Code of Conduct file][9]
* [Add a Contributing file][10]
* [Add a LICENSE file - LGPL by default][11]
* [Add `ISSUE_TEMPLATE.md` and `PULL_REQUEST_TEMPLATE.md` files][12]
* [Add a `README.md` file][13]
* [Add Travis CI badge to `README.md`][14]
* Do not require [signed commits][githubsignedcommits]

[1]: https://chris.beams.io/posts/git-commit/#seven-rules
[2]: https://help.github.com/articles/signing-commits-using-gpg/
[3]: http://nvie.com/posts/a-successful-git-branching-model/
[4]: https://blog.golang.org/go-fmt-your-code
[5]: https://github.com/golang/dep
[6]: https://travis-ci.org/
[7]: https://www.docker.com/
[8]: https://hub.docker.com/
[9]: https://help.github.com/articles/adding-a-code-of-conduct-to-your-project/
[10]: https://gist.github.com/PurpleBooth/b24679402957c63ec426
[11]: https://help.github.com/articles/adding-a-license-to-a-repository/
[12]: https://blog.github.com/2016-02-17-issue-and-pull-request-templates/
[13]: https://gist.github.com/PurpleBooth/109311bb0361f32d87a2
[14]: https://docs.travis-ci.com/user/status-images/
[15]: http://solidity.readthedocs.io/en/develop/style-guide.html
[16]: https://consensys.github.io/smart-contract-best-practices/
[solhint]: https://github.com/protofire/solhint
[PEP8]: https://www.python.org/dev/peps/pep-0008/
[pylint]: https://www.pylint.org/
[eslint]: https://eslint.org/
[eslint_airbnb]: https://github.com/airbnb/javascript
[mozilla_es6]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/New_in_JavaScript/ECMAScript_2015_support_in_Mozilla
[official_es6]: http://www.ecma-international.org/ecma-262/6.0/index.html
[mozilla_webcomponents]: https://developer.mozilla.org/en-US/docs/Web/Web_Components
[githubsignedcommits]: https://help.github.com/articles/enabling-required-commit-signing/
[sm_desc]: SMART_CONTRACT_DESCRIPTION.md
