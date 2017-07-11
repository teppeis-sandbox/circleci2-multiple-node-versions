circleci2-multiple-node-versions
====
Sample project to build with multiple Node.js versions in CircleCI 2.0

[![build status][circleci-image]][circleci-url]
![Node.js Version Support][node-version]

## How to use

1. [Add your project to CircleCI](https://circleci.com/docs/2.0/first-steps/)
2. Open your project settings in CircleCI 2.0 and add a new "Environment Variables"
  - name: `CIRCLE_CACHE_VERSION`, value: 1
3. Rebuild

## License

MIT License: Teppei Sato &lt;teppeis@gmail.com&gt;

[circleci-image]: https://circleci.com/gh/teppeis-sandbox/circleci2-multiple-node-versions.svg?style=svg
[circleci-url]: https://circleci.com/gh/teppeis-sandbox/circleci2-multiple-node-versions
[node-version]: https://img.shields.io/badge/Node.js%20support-v4,v6,v8-brightgreen.svg
